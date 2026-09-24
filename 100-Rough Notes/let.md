---
id: let
aliases:
  - let
tags:
  - javascript
created: "22-09-2026 20:54"
status: learn
---

# let

it is a modern way to declare variables in js and was introduced in (ES6).

1. it provides block-level scoping.
2. it is help full to avoid unintended issues caused by variable hoisting and scope leakage that are common with var.

```js
let variable = value;
```

## key Features of let

- Block [[Scope]] --> variable declared with let key word is block-scoped, they are only accessible within the block,statement or expression where they are defined.

- No Redeclaration --> can't redeclare a variable with let in the same scope.

```js
let z = 30;
//let z = 40; // throws error because redeclaring variable with the key word let is not allowed unlike var.
z = 40; // but reassigning is allowed just as var key word
```

- No [[Hoisting|Hosting]] Issues --> variables declared with let are hoisted but remain uninitialized (==which mean we can't access it until the declaration line==), which will avoid accidental access before declaration.this is know as **temporal dead zone**

## References

[let](https://www.geeksforgeeks.org/javascript/javascript-let/)
