node.js ES6
=======

The following video provides directions how to install Babel to run ES6 on Node.js. Apparently, ES6 is not yet supported on Node.js.
https://egghead.io/lessons/node-js-using-es6-and-beyond-with-node-js

### check scripts under package.json

```json
  "scripts": {
    "dev": "nodemon --exec babel-node src/app.js",
    "prestart": "babel src --out-dir dist",
    "start": "node dist/app.js"
  }
```