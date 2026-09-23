---
id: Local-Storage
aliases:
  - local
tags:
  - web-development
---

18-09-2026 18:12
Status: _writing_

# Local-Storage

The **localstorage** read-only property of the window interface allows you to access a Storage object for the Document's origin the stored data is saved across browser session.**localStorage** is similar to [[Session-Storage]], expect that while localstorage data has no expiration time, **sessionStorage** data gets cleared when the page session ends. Data stored in the local storage can be accessed throughout a particular domain.

> [!IMPORTANT]
> usage :
>
> 1. only use local storage when storing insensitive information.
> 2. thrid party individuals can easily access the information.
> 3. local storage can be helpful in storing temporary data before it is pushed to the sever.
> 4. it's important to clear the local storage once this operation is completed.

> [!WARNING]
> There are certain limitations of local storage :
>
> 1. Insecure data.
> 2. Synchronous operations.
> 3. Limited storage capacity.

## Web Storage Objects methods

[[Object-Method]]

- **localStorage** : to display the localStorage object
- **localStorage.clear()** : to remove everything in the local storage
- **localStorage.setItem()** : to store data in the localStorage. It takes a key and value parameters.
- **localStorage.getItem()** : to display data stored in the localStorage. It takes key as a parameter.
- **localStorage.removeItem()** : to remove stored item form a localStorage. it takes key as parameter.
- **localStorage** : to display a data stored in a localStorage. It takes index as a parameter.

> [!NOTE]
> local storage only stores strings so, if you wish to store objects, lists, or arrays, it must be converted to a string using **JSON.stringify().** There are two methods for this which is listed below,

1. [[JSON-serialization]]
2. [[JSON-deserialization]]

---

## References

Storage](../800-Refernces/sotage.pdf)
