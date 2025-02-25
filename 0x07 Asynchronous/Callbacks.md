## Callbacks

- Callbacks are a way to pass a function as an argument to another function.

Example

```javascript
function fetchData() {
    let data = { username: "Nderi Muya", role: "Admin" };
    return data;
}

function showData(data) {
    console.log(`Username is ${data.username} and role is ${data.role}`);
}

const userData = fetchData();
showData(userData);
```
-Imagine fetchData() is modified to simulate an API request using setTimeout:

Example

```javascript
function fetchData() {
  setTimeout(() => {
    let data = { username: "Nderi Muya", role: "Admin" };
    return data;
  }, 2000);
}

function showData(data) {
  console.log(`Username is ${data.username} and role is ${data.role}`);
}

const userData = fetchData();
showData(userData);
```
- A call back function is a function that is passed as an argument to another function and is executed after the other function has completed its execution.

Example

```javascript
function fetchData(callback) {
  setTimeout(() => {
    let data = { username: "Nderi Muya", role: "Admin" };
    callback(data);
  })
}

function showData(data) {
  console.log(`Username is ${data.username} and role is ${data.role}`);
}
```
-Assuming we are fetching data with multiple data points:

- fetch user data (e.g., username and role)

- Fetch user's posts after getting user data

- Fetch comments on a post after retrieving posts

- Display all the data after everything is fetched.

- Using callbacks, your code will look like this:

```javascript
function fetchUser(callback) {
  setTimeout(() => {
    console.log("Fetched user data");
    let user = { username: "Nderi Muya", role: "Admin" };
    callback(user);
  }, 2000);
}

function fetchPosts(user, callback) {
  setTimeout(() => {
    console.log(`Fetched posts for ${user.username}`);
    let posts = ["Post 1", "Post 2", "Post 3"];
    callback(posts);
  }, 2000);
}

function fetchComments(post, callback) {
  setTimeout(() => {
    console.log(`Fetched comments for ${post}`);
    let comments = ["Great work!", "Wow!", "Interesting"];
    callback(comments);
  }, 2000);
}

// Callback Hell (Nested Callbacks)
fetchUser((user) => {
  fetchPosts(user, (posts) => {
    fetchComments(posts[0], (comments) => {
      console.log(`User: ${user.username}, Role: ${user.role}`);
      console.log(`Posts: ${posts}`);
      console.log(`Comments on first post: ${comments}`);
    });
  });
});
```
The problems with the code above are:

- The indentation (callback hell) keeps increasing making the code harder to read.

- Difficult debugging: If something goes wrong, finding the issue in nested callbacks is frustrating.

- If we add more steps (e.g., fetch likes, fetch friends), the nesting increases further.

To avoid callback hell, we can replace callbacks with Promises, which provide better structure and readability.


