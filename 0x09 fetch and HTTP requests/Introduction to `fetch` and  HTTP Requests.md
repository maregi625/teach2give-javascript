## Introduction to `fetch` and HTTP Requests
-`fetch` is a built-in JavaScript function that allows your code to communicate with other computers (servers) over the internet.

-It helps your code send and receive data from websites or APIs (Application Programming Interfaces).

-Think of it like asking a friend for information:

- You ask: "Hey, what is the weather today"

- They respond: "It’s sunny and 25°C."

Similarly, fetch sends a request to a website (server), and the server responds with some data.

## HTTP Requests
-HTTP (Hypertext Transfer Protocol) is a protocol for sending and receiving data over the internet.

-It is the standard protocol for communication between web browsers and web servers.

-There are three types of requests:

- GET: retrieve data from a server.

- POST: send data to a server.

- DELETE: delete data from a server.

-PUT: update data on a server.

-HEAD: retrieve the headers of a server response.

## Making a simple fetch request

-Let's make a simple fetch request to get data from a public API (a website that shares data).

We'll use jsonplaceholder.typicode.com, which gives fake user data.

Example

```JavaScript
fetch("https://jsonplaceholder.typicode.com/users")
  .then(function (response) {
    return response.json();
  })
  .then(function (data) {
    console.log(data);
  })
  .catch(function (error) {
    console.log("There was an error");
    console.log(error);
  });
  ```
 ## Using async await for easier syntax

 - Instead of using callbacks, we can use async/await to make our code more readable and easier to understand.

Example

```JavaScript
async function fetchData() {
  try {
    const response = await fetch("https://jsonplaceholder.typicode.com/users");
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.log("There was an error");
    console.log(error);
  }
}
fetchData();
```
## Handling errors

- If we want to handle errors, we can use the `catch` method.

Example

```JavaScript
fetch("https://jsonplaceholder.typicode.com/users")
  .then(function (response) {
    return response.json();
  })
  .then(function (data) {
    console.log(data);
  })
  .catch(function (error) {
    console.log("There was an error");
    console.log(error);
  });
  ```

