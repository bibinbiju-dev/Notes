---
id: notes
aliases: []
tags: []
---

Uses in client-server applications to build server with node js features
steps to create express server for resolving client request

- create a server folder for application
- inside server folder, create package.json file: using command : npm init -y
- update package.json script with object start as key and values as node index.js and remove test key from it
- install packages needed to build express js server
  - express package (used to create server) : npm i express
  - cors package (used to share data between client & server app) : npm i cors
  - dotenv package (used to load .env file content initially to the server app) : npm i dotenv
- create .env file (used to store environmental variables ) in server folder.
- create .gitignore (used to store files/folders to be ignored while adding to git) file in server folder and add (node_modules, .env)
- create index.js file server to define express server
  - import dotenv,cors,express
  - create server using express
  - use cors in server app
