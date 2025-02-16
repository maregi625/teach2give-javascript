## String Concatenation
- String concatenation is the process of joining two or more strings into a single string.
1) Using the `+` operator

-It adds the value of the right operand to the end of the value of the left operand.

Example

```javascript
let name = "jackie";
let age = 20;
console.log("My name is " + name + " and I am " + age + " years old"); // Output: My name is jackie and I am 20 years old
```

2) Using the `+=` operator

-It adds the value of the right operand to the end of the value of the left operand.

Example

```javascript
let place = "Nairobi";
let age = 20;
place += " and I am " + age + " years old"; // place will be "Nairobi and I am 20 years old"
```
3) Using Template Literals

-Template literals are strings that allow you to embed expressions inside them.

Example

```javascript
let car = "Isuzu";
let currency = 30;
console.log(`My car is ${car} and currency is ${petrol} 30 dollars); // Output: My car is isuzu and currecy is 30 dollars
```

4) Using the `concat()` method

-It adds the value of the right operand to the end of the value of the left operand.

Example

```javascript
let name = "jackie";
let age = 20;
console.log("My name is ".concat(name).concat(" and I am ").concat(age).concat(" years old")); // Output: My name is jackie and I am 20 years old
``` 

