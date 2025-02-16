# variables
Variables are used to store data values.They can store and retrieve data from a computer's memory.

# Declaring variables in a Javascript
It can be declared using var, let, or const keywords.

Example

```javascript
men = 70; // A variable named "men" holding the value 70
const name = "Nderi"; // A constant variable holding a text value
var city = "Ngoi"; // Old way of declaring variables

```
## Updating variables
Using `let` and `var` you can update a variable's value.

Example

```javascript
let exam;=5xexam = 50; // Now the value of "exam" is updated to 50

var participant = "JC";
participants = "50 srudents";

```
But `const` cannot be changed once assigned

Example
```javascript

const religion = "muslim";
country = "christian"; // ❌ This will cause an error!
```
# Declaring vs.initializing variables

## -declaring variables
-it tells Javascript that a variable exists, but it does not have any value left.

Example
```javascript
let census; // Declared but not initialized
console.log(census); // Output: undefined
```

## -initializing variables
-it assigns a value to a variable.

Example
```javascript
let census = 50; // Declared and initialized
console.log(census); // Output: 50
```
NOTE BETTER

`const` variables cannot be changed once assigned, but `let` variables can be changed.

# Rules for naming variables
Variables can be named with numbers, letters, and underscores. They cannot start with a number, and they cannot contain spaces.

Example
```javascript

let name = "Nderi";
let age = 20;
let city = "Ngoi";

```
Point to note

Variable names can only contain letters, numbers, and underscores. They cannot start with a number or underscore.

Example (valid example)

```javascript

let population = "60";
let total population ="100";
let per county = "10";
```
(Itnvalid example)

```javascript

let 1population = "60"; // Invalid because it starts with a number
let total population ="100"; // Invalid because it contains a space
```
Point to note

-Variablee names are case-sensitive therefore one should use meaningful and descriptive names.If a variable is made up of multiple words, use the `camel case convention`.
