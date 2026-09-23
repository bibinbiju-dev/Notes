---
id: JSON-deserialization
aliases: []
tags:
  - storage
---

**Deserialization** --> Converting the stored representation by done [[JSON-serialization]] back into javascript object. ie, in simple words it coverts json string into the original js object.

```js
JSON.parse();
```

Consider the js object given below;

```js
let userStr = { name: "Sammy", email: "sammy@example.com", plan: "pro" };
let userObj = JSON.parse(userStr);
console.log(userObj);
```

The out-put from the above code will be like

```js
{name:"Sammy",
  email:"sammy@example.com",
plan:"Pro"
}
```
