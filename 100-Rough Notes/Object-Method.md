---
id: Object-Method
aliases: []
tags:
  - storage
---

# Methods

[[Local-Storage]] is a storage object, and it provides a small set of methods/properties for working with stored key-value data.

## key()

- This method is used to retrieve a value/string form a specific location.
- An index is passed into the key() function as a parameter.
- it can also be used in a loop statement to retrieve all the items in the local storage.

Suppose the items are stored in the local storage.

```js
localStorage.setItem("name", "Bibin");
localStorage.setItem("age", "22");
localStorage.setItem("theme", "dark");
```

i can get the key using the index like

```js
localStorage.key(0);
// we will get the key name

localStorage.key(1);
// key age
```

We can also apply loop statement to get all the keys or specific amount of keys

```js
for (let i = 0; i < localStorage.length; i++) {
  console.log(localStorage.key(i));
}
```

## setItem()

- it is used to store items in local storage.
- before storing item using this method we first stringify the js object with [[JSON-serialization]] ie, convert it into JSON string.

```js
const Car = {
  brand: "Suzuki",
  color: "white",
  price: 10000,
};
localStorage.setItem("car", JSON.stringify(Car));
```

## getItem()

- it is used to access or retrieve the data in the local storage.
- it takes key as a parameter. And then extracts the required value from the local storage.

```js
localStorage.getItem("grade");
//or
JSON.parse(localStorage.getItem("car"));
```

## removeItem()

- used to delete an item from local storage.
- it also requires key as a parameter.

```js
localStorage.removeItem("band");
```

## clear()

- used to clear all values stored in local storage.
- don't need any parameter.

```js
localStorage.clear();
```
