## Sets 

- A set is a collection of unique elements.

- Sets are used to store unique values.

## Properties of a set

- A set is unordered.

- A set cannot have duplicate values.

- A set is iterable.

## Creating a set

- A set can be created using the `new Set()` constructor.

Example

```javascript
const fruits = new Set(["apple", "banana", "orange"]);
console.log(fruits); // Set(3) {"apple", "banana", "orange"}
```

## delete (value)

- The `delete()` method removes a value from a set.

Example

```javascript
const fruits = new Set(["apple", "banana", "orange"]);
fruits.delete("apple");
console.log(fruits); // Set(2) {"banana", "orange"}
```

## has (value)

- The `has()` method returns true if a value exists in a set.

Example

```javascript
const fruits = new Set(["apple", "banana", "orange"]);
console.log(fruits.has("apple")); // true
console.log(fruits.has("kiwi")); // false
```

## size

- The `size` property returns the number of elements in a set.

Example

```javascript
const fruits = new Set(["apple", "banana", "orange"]);
console.log(fruits.size); // 3
```






