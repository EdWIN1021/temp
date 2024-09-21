# NextAuth

## Configuration

install NextAuth

```bash
npm install next-auth
```

create `route.ts` in `/app/api/auth/[...nextauth]`

```tsx
import NextAuth, { NextAuthOptions } from "next-auth";

//providers
import GithubProvider from "next-auth/providers/github";
import GoogleProvider from "next-auth/providers/google";
import CredentialsProvider from "next-auth/providers/credentials";

//prisma
import { PrismaAdapter } from "@next-auth/prisma-adapter";
import { PrismaClient } from "@prisma/client";

export const authOptions: NextAuthOptions = {
  adapter: PrismaAdapter(prisma), // prisma
  providers: [
    GithubProvider({
      clientId: process.env.GITHUB_ID as string,
      clientSecret: process.env.GITHUB_SECRET as string,
    }),
    GoogleProvider({
      clientId: process.env.GOOGLE_ID as string,
      clientSecret: process.env.GOOGLE_SECRET as string,
    }),
    CredentialsProvider({
      name: "Credentials",
      credentials: {
        email: { label: "email", type: "text" },
        password: { label: "password", type: "password" },
      },
      async authorize(credentials) {
                //verify user and returen it

        return user;
      },
    }),
  ],
};

const handler = NextAuth(authOptions);

export { handler as GET, handler as POST };
```

add keys to .env file

```tsx
GITHUB_ID="59299e15c10941068c66"
GITHUB_SECRET="0c61be57ecd75079dd4fb91f8145787f4e9cf56b"

GOOGLE_ID="199314165178-quodb4uj1fqbc8hrlh8db5l845tiksti.apps.googleusercontent.com"
GOOGLE_SECRET="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"
```