---
id: const
aliases:
  - const
tags:
  - javascript
created: "22-09-2026 20:55"
status: learn
---

[[variables]]

# const

we use `const` key word in-order to declare a constant ==unchanging== variable. a variable declared using the key word const can't be reassigned. it was introduced in (ES6) just like let.

- it is block-[[scope]] similar to let.
- it ensures immutability variable value.
- it can't be reassigned and redeclared.
- it must be initialized, unlike let a const variable must be initialized at the time of declaration.
- the main use of const variable is that we can make safer functions. ie it ensures that the function reference cannot be reassigned.

- [[hosting]] --> variables declared with const are hoisted to the top of their block but cannot be accessed until they are initialized, resulting in a **temporal dead zone** just like let variable.

```js
const pi = 3.14; // both redeclaration and reassignment of variable  is not allowed
//pi = "y"; // throws an error
console.log(pi);
```

## References
