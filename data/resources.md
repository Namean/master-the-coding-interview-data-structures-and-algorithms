

context: How to use module.exports / require
query: module.exports
title: module.exports – How to Export in Node.js and JavaScript
url: https://www.freecodecamp.org/news/module-exports-how-to-export-in-node-js-and-javascript/
author: Dillion Megida


```js


module.exports = { replaceStr}
// or
exports.replaceStr = replaceStr


const { replaceStr } = require('./utility.js');


```


### module.exports vs exports in Node
They're pretty much the same.


context: How to use object destructuring
query: object destructring javascript
title: Destructuring assignment
url: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment




```js

let a, b, rest;
[a, b] = [10, 20];

[a, b, ...rest] = [10, 20, 30, 40, 50]; // Expected output: Array [30, 40, 50]

const x = [1, 2, 3, 4, 5];
const [y, z] = x;
console.log(y); // 1
console.log(z); // 2


const obj = { a: 1, b: 2 };
const { a, b } = obj;





```






### Object destructuring

#### Basic assignment

```js

const user = {
  id: 42,
  isVerified: true,
};

const { id, isVerified } = user;

console.log(id); // 42
console.log(isVerified); // true

```






