## Objects

- Objects are a collection of key-value pairs.

- They are used to store data in a structured way.

- They are used to represent real-world entities.

- They are used to represent complex data structures.

- They are used to represent objects in programming.

## Creating Objects
-JavaScript provides the following ways to create objects:

- An object literal

- Using the `Object.create()` method

- Using a constructor function

## An object literal
- An object literal is a JavaScript object created using curly braces `{}`.

Example

```javascript
const person = {
person.name: "John",
person.age: 30,
    city: "New York"
};
```

## Using the `Object.create()` method

- The `Object.create()` method creates a new object with the specified prototype and properties.

Example

```javascript
const person = Object.create({
    name: "John",
    age: 30,
    city: "New York"
}); 
```

## Using a constructor function

- A constructor function is a function that is used to create objects.

Example

```javascript
function Person(name, age, city) {
    this.name = name;
    this.age = age;
    this.city = city;   
}
```

## Accessing Object properties

-There are two ways of accessing object properties:

- Dot notation

- Bracket notation

## Dot notation

- Dot notation is used to access properties of an object.

Example

```javascript
const person = {
    name: "John",
    age: 30,
    city: "New York"
};
console.log(person.name); // Output: "John"
```

## Bracket notation

- Bracket notation is used to access properties of an object.

Example

```javascript
const person = {
    firstName: "nderi",
    lastName: "muya",
    age: 30,
    city: "Nairobi"
    isAlive: true
    greeting: function() {
        console.log("Hello, my name is " + this.firstName + " " + this.lastName);
    },
};
```

## Modifying objects

<h1>Adding new properties</h1>

You can use the dot or bracket notation to add new properties to an object.

Example

```javascript
const person = {
    name: "John",
    age: 30,
    city: "New York"
};
person.country = "USA";
console.log(person); // Output: {name: "John", age: 30, city: "New York", country: "USA"}
```

<h1>Updating properties</h1>

You can use the dot or bracket notation to update existing properties of an object.

Example

```javascript
const person = {
    firstName: "nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    cosole.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true}
```

<h1>Deleting properties</h1>

You can use the delete keyword to delete properties of an object.

Example

```javascript
const person = {
   firstname: "Nderi",
   lastname: "Muya",
   age: 30,
   isAlive: true
   console.log(person); // Output: {firstname: "Nderi", lastname: "Muya", age: 30, isAlive: true}
};
delete person.isAlive;
```

## Checking properties in an object

-To check if a certain property is available in an object, you can use:

- The `in` keyword.

- The `hasOwnProperty()` method.

## The `in` keyword

- The `in` keyword is used to check if a certain property is available in an object.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true}
};
if ("isAlive" in person) {
    console.log("isAlive is a property of the person object");
} else {
    console.log("isAlive is not a property of the person object");
}
```

## The `hasOwnProperty()` method

- The `hasOwnProperty()` method is used to check if a certain property is available in an object.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true}
};
if (person.hasOwnProperty("isAlive")) {
    console.log("isAlive is a property of the person object");
} else {
    console.log("isAlive is not a property of the person object");
}
```

## Object Methods

- An object method is a function that is defined inside an object.

<h1>object.keys(object name)</h1>

- The `object.keys()` method returns an array of the keys of an object.

Example 

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true}
};
const keys = Object.keys(person);
console.log(keys); // Output: ["firstName", "lastName", "age", "isAlive"]
```

<h1>object.values(object name)</h1>

- The `object.values()` method returns an array of the values of an object.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true};
};
const values = Object.values(person);
console.log(values); // Output: ["Nderi", "Muya", 30, true]
```

<h1>object.entries(object name)</h1>

- The `object.entries()` method returns an array of the key-value pairs of an object.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true};
};
const entries = Object.entries(person);
console.log(entries); // Output: [["firstName", "Nderi"], ["lastName", "Muya"], ["age", 30], ["isAlive", true]]
```

<h1>object.freeze(object name)</h1>

- The `object.freeze()` method prevents the modification of an object.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true};
};
Object.freeze(person);
person.firstName = "John";
console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true}
```

## Iterating over an object using the `for...in` loop

- The `for...in` loop is used to iterate over the properties of an object.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true};
};
for (let key in person) {
    console.log(key); // Output: "firstName", "lastName", "age", "isAlive"
    console.log(person[key]); // Output: "Nderi", "Muya", 30, true
}
```


















