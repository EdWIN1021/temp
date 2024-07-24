Dump cache for everything in a page

```ts
import { revalidatePath } from "next/cache"; 

revalidatePath("/");
```