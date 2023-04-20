# 🦌&nbsp;TypeScript

## TypeScript 5.0 Beta
All release you can check [here](https://devblogs.microsoft.com/typescript/announcing-typescript-5-0-beta/) 

- [`const` Type Parameters](https://devblogs.microsoft.com/typescript/announcing-typescript-5-0-beta/#const-type-parameters)
TS5.0 recognises parameters for inference if we add const before the parameter
Seems like handling of generics with literal values get easier and we would get more accurate error message


 
## 🙂&nbsp;Terminologies
- `transpile`: Converting next-generation TypeScript/JavaScript to an old version of JavaScript that works in browsers
- `compile`: Code generation. Making output from the source code.

## 🗽&nbsp;Code with TypeScript type errors can produce out put

### `tsc` does two things

- transpiling
- checking type errors 

☝️&nbsp;These two are entirely independent. In other words, _code output is independent of type checking_.
During compile, `interface`, `type`, and `type annotation` are removed from your code. So, **you cannot check type check on runtime**.

## 🐌 Escaping apostrophe in single quoted string
- Use `\`
  - Example: `I\'m happy.`
