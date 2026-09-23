---
id: JSON-serialization
aliases: []
tags:
  - storage
---

**Serialization** --> converting an object into a storable/transmittable format.
ie, JSON.stingify() takes a javascript object and transforms it into a JSON string.
It is the opposite of [[JSON-deserialization]]

```js
JSON.stringify(object);
```

Consider the js object given below the JSON.stringify() method converts it into a json file.

```js
let userObj = {
  name: "Sammy",
  email: "sammy@example.com",
  plan: "Pro",
};
let userStr = JSON.stringify(userObj);
console.log(userStr);
```

The code above will convert the usrObj object into json data

```json
{ "name": "Sammy", "email": "sammy@example.com", "plan": "pro" }
```
