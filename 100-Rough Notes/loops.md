---
id: loops
aliases: []
tags:
  - javascript
---

loops are used to repeat an actions. in other words loops are a way to repeat the same code multiple times.

## types of loops

1. while loop
2. do while loop
3. for loop

## while loop

while loop executes the code body while the condition is truthy. in theory if don't set a limit while loop while execute the code forever.

==syntax==

```js
while (condition) {
  // code
}
```

```js
let i = 0;
while (i < 3) {
  console.log(i);
  i++;
}
// here if we leave out the i++ part i will never be 3 or more than 3. in theory the while loop will run forever.
```

## do while loop

it is an extends of while loop. while loop first checks the condition and executes the code if the condition is true but in do while loop the code is executed first and then checks the condition. in while loop the code is executed if and only if the condition is truthy, but in do while loop the code is executed at least once even if the condition is false.

## for loop

it is more complex than while loop and it's the most used one. it is used when we need to control the counter(control how may times something runs).

==syntax==

```js
for (initalialization; condition; update) {
  // loop body
}
// example
for (let i = 0; i < 3; i++) {
  console.log(i);
}
```

| part             | syntax         | what it does                                                 |
| ---------------- | -------------- | ------------------------------------------------------------ |
| initalialization | let i=0        | executes once upon entering the loop.                        |
| condition        | i<3            | checks before every loop iteration. if false, the loop stops |
| body             | console.log(i) | runs again and agin while the condition is truthy.           |
| update           | i++            | executes after the body on each itration                     |

### for of loop

- this is use full with arrays.
- used when we only care about the value.
- loops through the value of an object.

```js
const numbers = [10, 20, 30, 40];
for (const number of numbers) {
  console.log(number * 2);
}
```

### for in loop

- use full for objects
- it gives you the index of the object.
- loops through key of an object.

```js
const person = {
  name: "Bibin",
  age: 22,
  country: "India",
};

for (const key in person) {
  console.log(key);
}
```

## breaking the loop

normally a loop exits when it's condition becomes falsy. we can also force the exit at any time using the special break directive.

```js
for (let i = 1; i <= 10; i++) {
  if (i === 5) {
    break;
  }

  console.log(i);
}
// when i becomes 5 break kills the loop
```

## continue loop

continue is different it skip the current iteration and moves to the next one.

```js
for (let i = 1; i <= 10; i++) {
  if (i % 2 !== 0) {
    continue;
  }

  console.log(i);
}
// here when i%2!==0  becomes true --> continue--> skip 1
// when i%2!==0  becomes false --> continue normally --> print 2
```
