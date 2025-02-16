## Type coersion and type conversion
- Type coersion is the automatic conversion of one data type to another data type.
- Type conversion is the manual conversion of one data type to another data type.   

## Type coersion(implicit type conversion)
- Type coersion is the automatic conversion of one data type to another data type.
- Type conversion is the manual conversion of one data type to another data type.   

Example

```javascript
let a = 20;
let b = "20";
console.log(a + b); // 2020
```

## Type conversion(explicit type conversion)
- Type coersion is the automatic conversion of one data type to another data type.

# Methods of type conversion

- converting using string method()

Example

```javascript
let a = 20;
let b = "20";
console.log(a.toString() + b); // 2020
```

- converting using number method(), ParseInt(), ParseFloat()

Example

```javascript
let a = "20";
let b = 20;
console.log(parseInt(a) + b); // 40
console.log(parseFloat(a) + b); // 40.0
``` 
-converting using boolean method()

Example

```javascript
let a = 20;
let b = "20";   
console.log(Boolean(a) + b); // true20
```
