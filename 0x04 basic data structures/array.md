## Arrays

-Arrays in javascript are used to store multiple values in a single variable.

-An array is a list of values.
## Creating an array

One can create an array using the following ways:

- An array literal
- An array constructor

##  Using an array literal

Example
```javascript

`const fruits = ["apple", "banana", "orange"];`
```

## Using an array constructor

Example

```javascript

`const fruits = new Array("apple", "banana", "orange");`
```
Point to note 

-`new Array()` constructor can also be nested.
-Always use array literal to create an array.

## Accessing array elements
-You can access an array element by using its index.
-The first element of an array has an index of 0.

Example

```javascript

`const fruits = ["apple", "banana", "orange"];
console.log(fruits[0]); // apple
console.log(fruits[1]); // banana
console.log(fruits[2]); // orange`
```

## Basic array methods
<h1>Length of an array</h1>

- You can get the length of an array using the `length` property.

Example

```javascript

`const fruits = ["apple", "banana", "orange"];
console.log(fruits.length); // 3`
``` 
<h1>pop</h1>

- The `pop()` method removes the last element from an array and returns that element.

Example

```javascript

`const fruits = ["apple", "banana", "orange"];
console.log(fruits.pop()); // orange
console.log(fruits); // ["apple", "banana"]`
```
Point to note
-The pop method returns the removed element.

<h1>push</h1>

- The `push()` method adds one or more elements to the end of an array and returns the new length of the array.

Example

```javascript

`const fruits = ["apple", "banana", "orange"];
console.log(fruits.push("kiwi")); // 4
console.log(fruits); // ["apple", "banana", "orange", "kiwi"]`
```
Point to note
- You can add elements to an array using the `push()` method.

<h1>shift</h1>

- The `shift()` method removes the first element from an array and returns that element.

Example

```javascript

`const fruits = ["apple", "banana", "orange"];
console.log(fruits.shift()); // apple
console.log(fruits); // ["banana", "orange"]`
```

<h1>unshift</h1>

- The `unshift()` method adds one or more elements to the beginning of an array and returns the new length of the array.

Example

```javascript

`const fruits = ["apple", "banana", "orange"];
console.log(fruits.unshift("kiwi")); // 4
console.log(fruits); // ["kiwi", "apple", "banana", "orange"]`
``` 

<h1>at()</h1>

- The `at()` method returns the element at the specified index in an array.

Example

```javascript

`const fruits = ["apple", "banana", "orange"];
console.log(fruits.at(0)); // apple
console.log(fruits.at(1)); // banana
console.log(fruits.at(2)); // orange`
```

<h1>join</h1>

- The `join()` method returns a string by concatenating all the elements of an array.

Example

```javascript

`const fruits = ["apple", "banana", "orange"];
console.log(fruits.join("++)); // apple++banana++orange
```

<h1>concat</h1>

- The `concat()` method returns a new array by merging two or more arrays.

Example

```javascript

`const fruits1 = ["apple", "banana", "orange"];
const fruits2 = ["kiwi", "pineapple", "grape"];
console.log(fruits1.concat(fruits2)); // ["apple", "banana", "orange", "kiwi", "pineapple", "grape"]`
```

<h1>flat</h1>

- The `flat()` method returns a new array with all sub-array elements concatenated into it recursively up to the specified depth.

Example

```javascript

`const fruits1 = ["apple", "banana", "orange"];
const fruits2 = ["kiwi", "pineapple", "grape"];
console.log(fruits1.flat()); // ["apple", "banana", "orange", "kiwi", "pineapple", "grape"]
```

<h1>indexof</h1>

- The indexOf() method is used to find the index of an element.

- It returns -1 if the element is not found.

Example

```javascript

const fruits = ["apple", "banana", "orange", "grape"];
console.log(fruits.indexOf("orange")); // 4
```

<h1>includes</h1>

- Checks if an element exists in an array.

- It returns true if it exists and false if it doesn't.

Example

```javascript

const fruits = ["apple", "banana", "orange", "grape"];
console.log(fruits.includes("apple")); // true
console.log(fruits.includes("mango")); // false
```

<h1>reverse</h1>

- Reverses the elements of an array.

Example

```javascript
const fruits = ["apple", "banana", "orange", "grape"];
console.log(fruits.reverse());
```



