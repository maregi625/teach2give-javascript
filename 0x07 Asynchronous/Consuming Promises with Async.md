## Consuming Promises with Async

`async/await` is the modern way to handle asynchronous operations in JavaScript. It allows you to write cleaner and more readable code.

Example

```javascript
function fetchUser() {
  return new Promise(function (resolve, reject) {
    let error = true;
    if (error === true) {
      reject("There was an error");
    } else {
      resolve({ username: "_Nderi", role: "Admin" });
    }
  });
}

async function processUser() {
  const user = await fetchUser();
  console.log(user);
}

processUser();
```

## Handling Errors with Async/Await
-One of the strengths of async/await is its ability to handle errors in a synchronous way, using `try...catch`.

Example

```javascript
async function processUser() {
  try {
    const user = await fetchUser();
    console.log(user);
  } catch (error) {
    console.error(error);
  }
  ```
  

}

