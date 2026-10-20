---
id: logical-operators
aliases: []
tags:
  - javascript
created: "25-09-2026 21:15"
status:
---

# Logical Operators

There are four logical operators in js

- `||` OR
- `&&` AND
- `!` NOT
- `??` Null Coalescing

## OR

```js
let result;
result = a || b;
```

it is used to manipulate boolean data. it returns true if one arguments is true and returns false if two arguments are false.

## Nullish Coalescing operator

it is written as two question marks ??.
the result of nullish Coalescing operator is a??b is

- if a is defined, then a.
- if a isn't defined, then b.

in other words it returns the first argument if it's not null/undefined otherwise, the second one is returned.

> [!NOTE]
> nullish Coalescing operator is like the OR operator but still there is a major difference between them
>
> - || returns the first truthy value.
> - ?? returns the first defined value.

```js
let height = 0;
console.log(height || 100); // 100
console.log(height ?? 100); // 0
//The height || 100 checks height for being a falsy value, and it’s 0, falsy indeed.
// so the result of || is the second argument, 100.
// The height ?? 100 checks height for being null/undefined, and it’s not,
// so the result is height “as is”, that is 0.
```

## References
