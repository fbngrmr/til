# Computed Property Names

ECMAScript 6 adds support for computed names in object property definitions when
using object literals.

```
const name = "bar";
const obj = {
    foo: "bar",
    [name]: 42
};
```
