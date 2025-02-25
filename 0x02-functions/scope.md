## Scope
-Scope in Javascript refers to the visibility of variables in a program.

-Javascript has the following types of scope:

- Global scope
- Function scope
- Block scope
- Lexical scope

## 1. Global scope

-Variables declared outside of any function or block are called global variables.

-Global variables can be accessed from anywhere in the program.

Example

```javascript
let week = "wednesday";

function exampleFunction() {
    console.log(week); // accesible inside function
}

exampleFunction(); // wednesday
console.log(week); // accessible outside function
```

## 2. Function scope

-Variables declared inside a function are called local variables.

-Local variables can only be accessed within the function in which they are declared.

Example

```javascript
function exampleFunction() {
    let week = "wednesday";
    console.log(week); // accessible inside function
}

console.log(week); // not accessible outside function
```

## 3. Block scope

-Variables declared inside a block are called block variables.
-A block is any code between curly braces `{}`.(e.g., in `if`, `for`, `while` statements

Example

```javascript
if (true) {
    let week = "wednesday";
    console.log(week); // accessible inside block
}

console.log(week); // not accessible outside block
``` 
-Point to note

- `var` does not follow block shape.

- `let` and `const` follow block shape.

## 4. Lexical scope

-Variables declared inside a function are called local variables.

-Local variables can only be accessed within the function in which they are declared.

-Variables declared outside of any function or block are called global variables.

Example

```javascript
function exampleFunction() {
    let week = "wednesday";
    function innerFunction() {
        console.log(week); // wednesday
    }
    innerFunction();    
}

parentFunction(); // wednesday
```









































































