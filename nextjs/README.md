# 🔼&nbsp;Next.js

---

- [If the child is a custom component that wraps an `<a>` tag](https://nextjs.org/docs/api-reference/next/link#if-the-child-is-a-custom-component-that-wraps-an-a-tag),
 you must add `passHref` to Link.
```ts
  <Link href="/products" passHref>
     <a className="font-bold underline" target="_blank"> 
        Products
    </a>
  </Link>
```
