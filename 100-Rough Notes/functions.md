---
id: functions
aliases: []
tags:
  - javascript
---

## functions

functions in js are reusable blocks of code designed to perform specific tasks. they allow you to organize, reuse, and modularize code. they can take inputs, perform actions, and return outputs.

```js
function greet(name) {
  console.log("hello" + name);
}
greet("alice");
```

- parameter : name (placeholder inside the function).
- argument : 'alice'( real value given at call time).
- return statement: used to send a result back from a function. when return executes the function stops running at that point. the returned value can be stored in a variable or used directly.

```js
function add(a, b) {
  return a + b;
}
let result = add(5, 3);
console.log(result);
```

## callback function

a call back function is a function that is passed as an argument for another function and is executed after the completion of that function.

## higher order function

a function that takes a another function as parameter or returns another function.
