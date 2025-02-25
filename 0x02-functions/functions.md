## Functions

A function is a block of code that is executed when it is called.

Functions help to break down a problem into smaller, manageable pieces.

The basic syntax of a function in Javascript is as follows:

```javascript
function functionName() {
    // function body
}
```
-To use a function, you must `call/invoke`the function

## Parameters Vs Arguments

- Parameters are placeholders for the values that will be passed to a function when it is called.
- Arguments are the actual values that are passed to a function when it is called.

Example

```javascript
function greet(week) { week is a parameter
    console.log(`Hae, " {week} week`);
    greet("wednesday"); // wednesday is an argument
}   
```
## Function Return Values

- A function can return a value to the caller.

Example

```javascript
function add(letter a, letterb) {
    return lettera + letterb;

}

let sum = add(10, 5);
console.log(sum);
```
## Categories of functions
-In programming, a function can be classified into the following categories:

1) Functions that do not take parameters(S) and do not return a value

2) Functions that do not take parameters(S) and return a value

3) Functions that take parameters(S) but do not return a value

4) Functions that take parameters(S) and return a value


## 1) Functions that do not take parameters(S) and do not return a value

Example

```javascript
function add() {
    let x = 10;
    let y = 5;
    console.log(x + y);
}
```

## 2) Functions that do not take parameters(S) and return a value

Example

```javascript
function add() {
    let x = 10;
    let y = 5;
    return x + y;
}

console.log(add());
```

## 3) Functions that take parameters(S) but do not return a value

Example

```javascript
function add(x, y) {
    console.log(x + y);
}
add(10, 5);
```

## 4) Functions that take parameters(S) and return a value

Example

```javascript
function add(x, y) {
    return x + y;
}

console.log(add(10, 5));
```

## Types of fuctions in Javascript

-There are five types of functions in Javascript, they include:
- Function declaration
- Function expression/anonymous function
- Arrow functions
- IIFE (Immediately Invoked Function Expression)
- Callback functions
## a) Function declaration

Example

```javascript
function add(x, y) {
    console.log(x + y);
}

add(10, 5);
```

## b) Function expression/anonymous function
It involves creating a function without a name to a variable

Example

```javascript
let add = function(x, y) {
    console.log(x + y);
}

add(10, 5);
```

## c) Arrow functions
Arrow functions are used to simplify the syntax of function expressions.

Example

```javascript
let add = (x, y) => {
    return x + y;
}

console.log(add(10, 5));
``` 
POINT TO NOTE

-If an arrow function has only one line in the body, the curly brackets can be omitted.
-If an arrow function has only one parameter, the parentheses can be omitted.

## d) IIFE (Immediately Invoked Function Expression)

Example

```javascript
(function(x, y) {
   let sum = x + y;
   let product = x * y;
   console.log(`The sum of ${x} and ${y} is ${sum}`);
   console.log(`The product of ${x} and ${y} is ${product}`);
})(10, 5);
```

## e) Callback functions

Example

```javascript
function greet(name, callback) {
    console.log(`Hello, ${name}`);
    callback();
    greet("nderi", function() {
        console.log("Goodbye!");
    })
}
``
