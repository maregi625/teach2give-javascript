## Object Literal Enhancements

- Object literal enhancements in JavaScript are a way to add new properties to an existing object without modifying the original object.
- They are often used to add new properties to objects that are created using object literal syntax.

## Shorthand Property Names

- Shorthand property names are a way to add new properties to an existing object without modifying the original object.
- They are often used to add new properties to objects that are created using object literal syntax.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
    console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true};
};
person.city = "Nairobi";
console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true, city: "Nairobi"};
```
## Method shorthand

- Method shorthand is a way to add new methods to an existing object without modifying the original object.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true,
    sayHello: function() {
        console.log("Hello, my name is " + this.firstName + " " + this.lastName);
    }
};
person.sayHello(); // Output: Hello, my name is Nderi Muya
```

## Computed Property Names

- Computed property names are a way to add new properties to an existing object without modifying the original object.

Example

```javascript
const person = {
    firstName: "Nderi",
    lastName: "Muya",
    age: 30,
    isAlive: true
};
person["city"] = "Nairobi";
console.log(person); // Output: {firstName: "Nderi", lastName: "Muya", age: 30, isAlive: true, city: "Nairobi"};
```
