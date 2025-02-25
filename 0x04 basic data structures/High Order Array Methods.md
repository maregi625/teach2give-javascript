## High Order Array Methods
-These methods simplify operations on arrays by allowing us to apply functions to elements directly, improving both readability and maintainability.

-They include:

1) ForEach

- Executes a function on each array element but does not return anything.

- Best used when you want to perform an action on each item.

- It does not create a new array.

Example

```javascript
const numbers = [1, 2, 3, 4, 5];
numbers.forEach(function(number) {
    console.log(number);
});
```

2) Map

- Creates a new array by applying a function to each element.

- It returns a new array.

- Best used when you want to create a new array based on the existing array.

Example

```javascript
const numbers = [3, 4, 5, 6,7];
const squaredNumbers = numbers.map(function(number) {
    console.log(squared);
    // output: [9, 16, 25, 36, 49]
});
```

   
3) Filter

- Creates a new array by filtering out elements based on a condition.

- It returns a new array.

- Best used when you want to create a new array based on a condition.

Example

```javascript
const numbers = [3, 4, 5, 6, 7,];
const evenNumbers = numbers.filter(function(number) {
console.log(evenNumbers);
// output: [4, 6]
});
``` 

4) Reduce

- Reduces an array to a single value by applying a function to each element.

- It returns a single value.

- Best used when you want to reduce an array to a single value.

Example

```javascript
const numbers = [3, 4, 5, 6, 7];
const sum = numbers.reduce(function(accumulator, number) {
console.log(sum);
// output: 20
}); 
```

5) Find

- Finds the first element that matches a condition.

- It returns the first matching element.

- Best used when you want to find the first element that matches a condition.

Example

```javascript
const numbers = [3, 4, 5, 6, 7];
const evenNumber = numbers.find(function(number) {
console.log(found);output: 4
});
```

5) FindIndex

- Finds the index of the first element that matches a condition.

- It returns the index of the first matching element.

- Best used when you want to find the index of the first element that matches a condition.

Example

```javascript
const numbers = [3, 4, 5, 6, 7];
const index = numbers.findIndex(function(number) {
console.log(index);
// output: 1
});
```

6) Some

- Checks if any element in the array matches a condition.

- It returns a boolean value.

- Best used when you want to check if any element in the array matches a condition.

Example

```javascript
const numbers = [3, 4, 5, 6, 7];
const hasEvenNumber = numbers.some(function(number) {
console.log(hasEvenNumber);
// output: true
});
```

7) Every

- Checks if all elements in the array match a condition.

- It returns a boolean value.

- Best used when you want to check if all elements in the array match a condition.


Example

```javascript
const numbers = [3, 4, 5, 6, 7];
const allEvenNumbers = numbers.every(function(number) {
console.log(allEvenNumbers);
// output: false    
});
```





