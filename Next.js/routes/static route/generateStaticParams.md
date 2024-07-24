
- only for production
- id has to be a sting


```ts
export async function generateStaticParams() {

  const snippets = await db.snippet.findMany(); 
  
  return snippets.map((snippet) => { 
    return { 
      id: snippet.id.toString()
    }; 
  }); 
}
```