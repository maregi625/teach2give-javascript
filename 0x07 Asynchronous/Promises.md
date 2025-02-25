## Promises
-When working with asynchronous code, we never know beforehand when we will get the results, also, we don't know if the results will be a success or a failure.

-When working with asynchronous JavaScript, there is the concept of producing code and consuming code.

- Producing code: is code that will take some time to complete e.g. fetching user information from a database.

- Consuming code: code that must wait for results from producing code

A promise is an object that links producing and consuming code.

-It is an object that also represents the eventual completion (or failure) of an asynchronous operation and its resulting value.

-It is a readable way to handle asynchronous operations compared to callbacks.

A promise has three states:

- Pending: initial state; neither fulfilled nor rejected.

- Fulfilled: the operation is completed successfully.

- Rejection: the operation has failed.

## Creating a Promise

-A promise is created using the `new Promise()` constructor.

-The constructor takes a function as an argument.

Example:

```JavaScript
const promise = new Promise((resolve, reject) => {
    // code to be executed
});
```

## Consuming a promise

-A promise can be consumed using the `then()` method.

- The `then()` method takes two arguments: a success callback and an error callback.

- The success callback is called when the promise is fulfilled, and the error callback is called when the promise is rejected.

Example:

```JavaScript
const promise = new Promise((resolve, reject) => {
    // code to be executed
});

promise.then((result) => {
    // code to be executed if the promise is fulfilled
}, (error) => {
    // code to be executed if the promise is rejected
}
})
```

## Returning a promise from a function

-A function can return a promise using the `return` keyword.


Example

```JavaScript
function fetchData() {
    return new Promise((resolve, reject) => {
        // code to be executed
    });
}
```

