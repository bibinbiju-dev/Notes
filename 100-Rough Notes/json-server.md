---
id: json-server
aliases: []
tags: []
---

## json-server

1. create a folder to hold json file
2. create package.json file inside the folder npm init -y
3. create db.json file inside the folder and resources as key to the json file
4. to run json file install json-server npm i json-server / npm i json-server@0.17.4
5. to run json file in localhost use npx json-server db.json / node index.js

## deploy a json file using node js

1. create index.js file server folder
2. update script in package.json file as "start":"node index.js"
3. create .gitignore file and add 'node modules' folder
4. define json-server to run json file in index.js
   - import json-server
   - create server run json file using create() method fo jsonServer
   - create middleware used by JSON Server.
   - set up route for json file in server
   - use middleware, route in server app
