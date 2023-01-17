# 🛩️ TailwindCSS
- `vw`*☝️mode: 'jit' should be enabled in your `tailwind.config.js`
  ```html
   <div className="m-[-50vw] w-[100vw]">{***}</div>
  ```
- Expand background of nexted children. 
     ```html
    <div className={`${backgroundColor} my-0 mx-[calc(50%_-_50vw)] w-[100vw]`}>
        <div className="m-auto max-w-5xl">
            {content}
        </div>
    </div>
    ```
