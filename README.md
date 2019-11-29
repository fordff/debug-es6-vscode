# debug-es6-vscode

Minimal Node.js with Babel Setup 

sample app for debug test bed in vscode 


Node : v 12.10.0

```
npm init -f
```

Babel.js : v 7.7.4

```
npm install @babel/core @babel/node --save-dev
npm install @babel/preset-env --save-dev
touch .babelrc

{
  "presets": [
    "@babel/preset-env"
  ]
}

touch .env

npm install dotenv --save


```


Nodemon : 

Babel is a JavaScript compiler
Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments. Here are the main things Babel can do for you:

- Transform syntax
- Polyfill features that are missing in your target environment (through @babel/polyfill)
- Source code transformations (codemods)
- And more! (check out these videos for inspiration)