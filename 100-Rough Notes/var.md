---
id: var
aliases: []
tags:
  - javascript
created: "22-09-2026 20:56"
status:
---

[[variables|variables]]

# var

**var** : Declares variables with function or global [[scope|scope]] and allows re-declaration and updates within the same scope. in simply words var allows both re-declaration and updates for variables.

```js
var x = 10;
var x = 20; //re-declaration allowed
x = 30; //update allowed
console.log(x); // o/p : 30

let y = 10;
let y = 20; // re-declaration not allowed

y = 25; // update allowed
console.log(y); // o/p: 25
```

## References

[var](https://www.geeksforgeeks.org/javascript/difference-between-var-let-and-const-keywords-in-javascript/)
