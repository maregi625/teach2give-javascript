## Default Parameters

- Default parameters are parameters that have a default value.
- If the parameter is not provided, the default value is used.

Example

```javascript   
function greet(name = "World") {
    console.log(`Hello, ${name}!`);
}
```
Point to note
-If no argument is provided, name defaults to "Guest" and if an argument is provided, it overrides the default value.

