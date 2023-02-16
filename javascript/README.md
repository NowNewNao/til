# 🦏&nbsp;JavaScript

Learning JavaScript basics

## 🤞What is `Promise`?

- An abstraction of asynchronous process in JavaScript

### How to use it?

- Instantiate `Promise` constructor
  - `new Primise()`
    - It has three status
      - `Fulfilled`
        - When `resolve` done. `value` will be passed, `onFulfilled` will be called.
      - `Rejected`
          - When `reject` done. `error` will be passed, `onRejected` will be called.
      - `Pending`
          - Except for the status at `FulFilled` or `Rejected` 
    - Once the state gets to `Fulfilled` or `Rejected`, it's never changed. Immutable.

 ## A little better Array method

### `filter` vs `some`
If you want to get an outcome as `boolean`, `some` is useful.
```ts
const givenArray = ['orange', 'banana', 'apple', 'grape', 'peach', 'pear', 'lemon', 'watermelon'];
const hasApple = givenArray.some(fruit => fruit === 'apple');
```
- When you use `filter`, instead of `some` for example, the all `givenArray` element are checked. And also, the return value is an array. `['apple']` in this case.
- Otherwise, if you use `some`, when `'apple'` is founded, immediately, `hasApple` become `true`. Faster and you will get `boolean` immediately!
