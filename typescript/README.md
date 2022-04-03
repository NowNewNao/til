# 🦌&nbsp;TypeScript

Learning TypeScript basics
 
## 🙂&nbsp;Terminologies
- `transpile`: Converting next-generation TypeScript/JavaScript to an old version of JavaScript that works in browsers
- `compile`: Code generation. Making output from the source code.

## 🗽&nbsp;Code with TypeScript type errors can produce out put

### `tsc` does two things

- transpiling
- checking type errors 

☝️&nbsp;These two are entirely independent. In other words, _code output is independent of type checking_.
During compile, `interface`, `type`, and `type annotation` are removed from your code. So, **you cannot check type check on runtime**.
