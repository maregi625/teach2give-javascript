## Conditionals

A conditional is a block of code that is executed only if a certain condition is true.

-Conditional statements in Javascript include:

- If statement
- Switch statement
- If else statement
- If else ladder

## 1. If statement

The if statement is used to execute a block of code if a certain condition is true.

Syntax is as follows

```javascript
if (condition) {
    // code to be executed if condition is true
}
```
Example in code form

```javascript
if (x > y) {
    console.log("x is greater than y");
}
```


## 2. Switch statement

The switch statement is used to execute a block of code based on different cases.

Syntax is as follows

```javascript
switch (expression) {
    case value1:
        // code to be executed if expression is equal to value1
        break;
    case value2:
        // code to be executed if expression is equal to value2
        break;
    default:
        // code to be executed if none of the cases match
}
``` 
Example in code form

```javascript
switch (x) {
    case 1:
        console.log("x is 1");
        break;
    case 2:
        console.log("x is 2");
        break;
    default:
        console.log("x is not 1 or 2");
}
```
## 3. If else statement

The if else statement is used to execute a block of code if a certain condition is true, and another block of code if the condition is false.

Syntax is as follows

```javascript
if (condition) {
    // code to be executed if condition is true
} else {
    // code to be executed if condition is false
}
```
Example in code form

```javascript
if (x > y) {
    console.log("x is greater than y");
} else {
    console.log("x is less than or equal to y");
}
``` 
## 4. If else ladder

The if else ladder is used to execute a block of code if a certain condition is true, and another block of code if the condition is false.

Syntax is as follows

```javascript
if (condition1) {
    // code to be executed if condition1 is true
} else if (condition2) {
    // code to be executed if condition1 is false and condition2 is true
} else {
    // code to be executed if condition1 is false and condition2 is false
}
```
Example in code form

```javascript
if (a > b) {
    console.log("a is greater than b");
} else if (a < b) {
    console.log("a is less than b");
} else {
    console.log("a is equal to b");
}
``` 
## Ternary Operator

The ternary operator is used to execute a block of code if a certain condition is true, and another block of code if the condition is false.

Syntax is as follows

```javascript
condition ? code to be executed if condition is true : code to be executed if condition is false;
```
Example in code form

```javascript
let a = 20;
let b = 5;
let result = a > b ? "a is greater than b" : "a is less than or equal to b";
console.log(result); // "a is greater than b"
```


    





