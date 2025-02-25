## ES6 Modules
- ES6 modules are a feature introduced in ECMAScript 2015 (ES6) and are a way to organize and manage code in JavaScript.
- They allow you to create and export modules, which can then be imported into other modules.

## Iportant Note About ES6 Modules
- ES6 modules are not the same as CommonJS modules.

- ES6 modules are a way to create and manage code in JavaScript.

-To use ES6 modules in Node.js:

a) Add "type": "module" in package.json.

b)Use .mjs files for ES6 modules.


## Exporting and Importing in ES6 Modules

- To export a value from an ES6 module, you use the export keyword followed by the value you want to export.

<h1Named Exports</h1>

Example

```javascript
export function add(a, b) {
  return a + b;
}

export function subtract(a, b) {
  return a - b;
}

export function multiply(a, b) {
  return a * b;
}

export function divide(a, b) {
    
}
```
## Importing everything as an object

- You can import all named exports as a single object.

Example

```javascript
import * as calculator from "./calculator.js";

console.log(calculator.add(2, 3)); // Output: 5
console.log(calculator.subtract(5, 2)); // Output: 3
console.log(calculator.multiply(3, 4)); // Output: 12
console.log(calculator.divide(10, 2)); // Output: 5
```

## Default Exports

- Each module can have one default export, which can be imported with any name.

-File: logger.mjs

Example

```javascript
export default function log(message) {
  console.log(message);
}
```
-File:index.mjs

Example

```javascript

import log from "./logger.mjs";

log("Hello, World");
```



