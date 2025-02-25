## Spread Operator

- The spread operator (...) allows you to expand elements of an iterable (like arrays, objects, or strings) into individual elements.

## Use cases of the spread operator

- The spread operator is often used in combination with other features in JavaScript, such as destructuring and the rest operator.

1) Expanding an Array

Example

```javascript
const numbers = [3, 4, 5];
const newNumbers = [...numbers, 5, 6];
console.log(newNumbers); // Output: [3, 4, 5, 6, 7,]
```

2) Copying an Array
- The spread Operator can be used to copy an array.

Example

```javascript
const numbers = [3, 4, 5];
const newNumbers = [...numbers];
console.log(newNumbers); // Output: [3, 4, 5]
```

3) Merging Objects

- Spread operator can be used to merge an array.

Example

```javascript

const arr1 = [3, 4, 5];
const arr2 = [6, 7, 8];
const merged = [...arr1, ...arr2];

console.log(merged); // [3, 4, 5, 6, 7 ,8]
```
4) Adding elements from one array to onother

```javascript
const numbers = [3, 4, 5];
const newNumbers = [2, ...numbers, 6];

console.log(newNumbers); // [2, 3, 4, 5, 6]
```

5) copying objects

```javascript
const person = {
    name: "Nderi",
    age: 30
};

const newPerson = {
    ...person,
    city: "Nairobi"
};

console.log(newPerson); // {name: "Nderi", age: 30, city: "Nairobi"}
```

6) Merging objects

```javascript
const obj1 = {a: 1, b: 2};
const obj2 = {c: 3, d: 4};

const merged = {...obj1, ...obj2};

console.log(merged); // {a: 1, b: 2, c: 3, d: 4}
```

7) overwriting properties

```javascript 
const obj1 = {a: 1, b: 2};
const obj2 = {a: 3, c: 4};

const merged = {...obj1, ...obj2};

console.log(merged); // {a: 3, b: 2, c: 4}
```
  



