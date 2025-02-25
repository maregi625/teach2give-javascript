## Rest Operator

- The rest operator (...) allows you to collect a variable number of arguments into an array.

## Use cases of the rest operator

- The rest operator is often used in combination with other features in JavaScript, such as destructuring and the spread operator.

1) Collecting a Variable Number of Arguments

Example

```javascript
function sum(...args) {
    let total = 0;
    for (let arg of args) {
        total += arg;
    }
    return total;
}

console.log(sum(1, 2, 3)); // 6
console.log(sum(1, 2, 3, 4)); // 10
```

2) Copying an Array

Example

```javascript
const numbers = [3, 4, 5];
const newNumbers = [...numbers];
console.log(newNumbers); // Output: [3, 4, 5]
```
