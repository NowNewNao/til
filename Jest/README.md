# 🎿Jest

### Environment Variable
If you used any environment variables in the tested code, you need to set it up for Jest as well.
If you used jest-shim.js, you could add it there, otherwise, in `.env.test`.
```ts
process.env.YOUR_ENV_NAME = 'true';
```

### Comparison methods
It is called as Matchers in Jest

There are three frequent used matchers, and those are easily making me confused when to use.

`toBe` `toEqual` `toStricEqual`

#### [`toBe`](https://jestjs.io/docs/expect#tobevalue)
Use this when you are comparing Primitive type such as `number` or `string`.

#### [`toEqual`](https://jestjs.io/docs/expect#toequalvalue)
Use this when you are comparing Object _value_.

#### [`toStricEqual`](https://jestjs.io/docs/expect#tostrictequalvalue)
Use this when you are comparing Object _type and value_.


A bit addition and modification for Jest example to understand clearer for me
```ts

class LaCroix {
  constructor(flavor) {
    this.flavor = flavor;
  }
}

describe('the La Croix cans on my desk', () => {
  test('are not semantically the same', () => {
    ✅ expect(new LaCroix('lemon')).toEqual({flavor: 'lemon'});
    ❌ expect(new LaCroix('lemon')).toStrictEqual({flavor: 'lemon'});  👈 Looks same, but different type
    ✅ expect(new LaCroix('lemon')).toStrictEqual({new LaCroix('lemon'));  👈 Looks same, AND the same type
  }); 
});

```
