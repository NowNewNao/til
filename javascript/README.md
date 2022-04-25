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
