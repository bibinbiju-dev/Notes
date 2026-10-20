---
id: React-js
aliases:
  - react
tags:
  - web-development
  - javascript
created: "25-09-2026 13:42"
status:
---

# React-js

- it is a javascript library for building user interfaces.
- ideal for building single-page applications (SPAs) and interactive web applications.

- it is the view layer web applications.

## key characteristics of SPA

- **no page reloads**
- **dynamic loading**
- **client-side routing**

## Components

- react app starts with a single root component.
- root component is build using one or more component
- each component can be nested with other components to any level.
- most of the components are user interface components.
- react app can include third party component for specific purpose such as routing, animation, state management, etc.

## vite installation

```zsh
npm create vite@latest

npm create vite@latest my-react-app --template react

cd my-project
npm run dev
```

## vite project folder structure

- **node_modules**
  - Contains all the dependencies that are needed for an intial working react app.
- **.gitignore(file)**
  - this file specifies intentionally untracked files that git should ignore.
- **package.json**
  - this file contains various metadata that is relevant to our project.

## Common tasks in front-end development

- App State : Data definition, organization, and storage.
- user actions : event handlers respond to user actions.
- templates : design and render html templates.
- routing : resolve urls
- data fetching : interact with server through api's and ajax.

**jsx** : jsx provides you to write html/xml then preprocessor will transform these expressions into actual js.

Virtual DOM : it is a lightweight copy of the actual DOM. it doesn't have power to directly change the layout of the document. when anything new is added to the application, a virtual DOM is created and it is represented as a tree. New virtual DOM tree is then compared with the previous virtual DOM tree and make a note of the changes. After this, it finds the best possible ways to make these changes to the real DOM. Now only the updated elements will rendered on the page again.This process of comparing the current virtual DOM tree with previous one is known as **diffing**. the entire process of transforming changes to the real DOM is called **Reconciliation**.

component rendering : when a component function executes we say it renders. assume components may re-render at any time our job ensures that every time the component re-renders the correct output is produced. In react everything is a component, it's the building blocks of a react application. They are reusable, self-contained pieces of code that encapsulate a part of the user interface and it's behaviour -.

functional component : these are javascript functions that returns jsx to describe the UI. primarily used for representing the UI and rendering content. they also make use of hooks to manage state and side effects.

class based components : these are js classes that extend react component and have for features compared to functional components. class based components can mange their own state implement lifecycle methods, and handle complex behaviour.

hooks: special functions that allow developers to hook into **state** and lifecycle of react components.
state : one or more data values associated with a react component instance. it represents the value of a dynamic properties of a react component at a given instance.
props : props stands for properties. props are component configuration. a component cannot change its props, but it is responsible for putting together the props of its child components. it can be data or even callback functions.

lifecycle: the events associated with a react component instance.

Controlled Components

- state management: form data is handled by the component's state using react's useState hook or this.state in class components.
- data flow: the input element's values are set by the state, and any changes are reflected through state updates.
- predictability: since the state is managed by React, the component's behavior is predictable and consistent.
- real-time validation : enables immediate validation and formatting of user input.
- single source of truth: the state serves as the single source of truth for the data.

## References
