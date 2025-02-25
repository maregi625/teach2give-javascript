## Asynchronous Javascript

- Asynchronous Javascript is a way to write code that can run in the background without blocking the main thread.

- JavaScript is inherently single-threaded and synchronous. This means it processes one task at a time sequentially.

- When a long-running task such as fetching data from a server or reading a file occurs, it can block the entire execution, making the application unresponsive, this is what asynchronous JavaScript solves

Example

```javascript

setTimeout(() => {
  console.log("Asynchronous JavaScript");
}, 2000);

console.log("javascript is fun");
console.log("I am learning javascript");

// Output:
// Hello World
// Goodbye World
// Asynchronous JavaScript
```

