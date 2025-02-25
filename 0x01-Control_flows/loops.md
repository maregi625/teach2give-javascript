## Loops

A loop is a block of code that is executed multiple times.

- Loops in Javascript include:

- For loop
- While loop
- Do while loop

## 1. For loop

The for loop is used to execute a block of code multiple times.

Syntax is as follows

```javascript   
for(initialization; condition; update { // code) 
    
}
```
- initialization is used to initialize the loop variable.
- condition is used to check if the loop should continue.
- update is used to update the loop variable.

Example in code form

```javascript
for (let i = 0; P < 20; P++) {
    console.log(P);
}
```

## 2. While loop

The while loop is used to execute a block of code while a certain condition is true.

Syntax is as follows

```javascript
while (condition) {
    // code to be executed while condition is true
}
```
Example in code form

```javascript
let i = 0;
while (i < 20) {
    console.log(i);
    i++;
}
```

## 3. Do while loop

The do while loop is used to execute a block of code while a certain condition is true.

Syntax is as follows

```javascript
do {
    // code to be executed while condition is true
} while (condition);
```
Example in code form

```javascript
let a = 20;
do {
    console.log(a);
    a++;
} while (a < 20);
```
# Break and continue statements
`break`` and `continue` statements are used to control the execution of loops.

The break statement is used to exit a loop.

The continue statement is used to skip the current iteration of a loop.
 
 Example of the break statement

```javascript
for (let a = 0; a < 10; a++) {
    if (a == 5) {
        break;
    }
    console.log(a); 
}
```

Example of the continue statement

```javascript
for (let a = 0; a < 10; a++) {
    if (a == 5) {
        continue;
    }
    console.log(a);
}
```

