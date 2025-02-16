## Operators
Operators are symbols used to perform operations on values, or to assign values to variables.

## Arithmetic Operators
-They are used to perform mathematical operations on numbers.
-They include:
1) `+` Addition

Example
```javascript
let x = 15;
let y = 10;
let c = a + b; // c will be 25 
```
2) `-` Subtraction

-It subtracts thevalue of the right operand from the value of the left operand.

Example

```javascript
let x = 15;
let y = 10;
let c = x - y; // c will be 5 
```

3) `*` Multiplication

-It multiplies the value of the left operand by the value of the right operand.

Example

```javascript
let x = 15;
let y = 10;
let c = x * y; // c will be 150
```

4) `/` Division

-It divides the value of the left operand by the value of the right operand.

Example

```javascript
let x = 15;
let y = 10;
let c = x / y; // c will be 1.5
```

5) `%` Modulus

-It returns the remainder when the value of the left operand is divided by the value of the right operand.

Example

```javascript
let x = 15;
let y = 10;
let c = x % y; // c will be 5
```

6) `**` Exponentiation

-It raises the value of the left operand to the power of the value of the right operand.

Example

```javascript
let x = 2;
let y = 3;
let c = x ** y; // c will be 8
```


## Assignment Operators
- They are used to assign values to variables.
- They include:

1) `=` Simple assignment operator

-The `=` operator is used to assign a value to a variable.
Example

```javascript
let a = 10;
```

2) Subtraction assignment operators (`-=)

-It subtracts the value of the right operand from the value of the left operand.

Example

```javascript
let a = 15;
let b = 10;
a  -= b; // x will be 5
```
3) Multiplication assignment operators (`*=)

-It multiplies the value of the left operand by the value of the right operand.

Example

```javascript
let a = 15;
let b = 10;
a *= b; // x will be 150
``` 

4) Division assignment operators (`/=`)

-It divides the value of the left operand by the value of the right operand.

Example

```javascript
let a = 15;
let b = 10;
a /= b; // x will be 1.5
```
## Comparison Operators
- They compare values and return a boolean value (true or false)
-They include:
1) Equality Operators

-It returns true if the values of two operands are equal, and false otherwise.

Example

```javascript
let x = 10;
lety y = 5;
console.log(a == b); // false
console.log(x == 10); // true    
```
2) Inequality Operators

-It returns true if the values of two operands are not equal, and false otherwise.

Example

```javascript
let x = 10;
let y = 5;
console.log(x != y); // true
console.log(x != 10); // false
```
3) Relational Operators

-They compare values and return a boolean value (true or false)

Example

```javascript
let x = 10;
let y = 5;
console.log(x > y); // true
console.log(x < y); // false
console.log(x >= y); // true
console.log(x <= y); // false
```
4) Strict Equality Operators

-It returns true if the values of two operands are strictly equal, and false otherwise.

Example

```javascript
let x = 10;
let y = 5;
console.log(x === y); // false
console.log(x === 10); // true
```
5) Strict Inequality Operators

-It returns true if the values of two operands are strictly not equal, and false otherwise.

Example

```javascript
let x = 10;
let y = 5;
console.log(x !== y); // true
console.log(x !== 10); // false
```
5) Relational Operators

-They compare values and return a boolean value (true or false)

Example

```javascript
let x = 10;
let y = 5;
console.log(x > y); // true
console.log(x < y); // false
console.log(x >= y); // true
console.log(x <= y); // false    
```
6) Logical Operators

-They compare values and return a boolean value (true or false)

Example

```javascript
let x = 10;
let y = 5;
console.log(x > 5 && y < 10); // true
console.log(x > 10 || y < 5); // false
```
7) Bitwise Operators

-They compare values and return a boolean value (true or false)

Example

```javascript
let x = 10;
let y = 5;
console.log(x & y); // 0
console.log(x | y); // 15
console.log(x ^ y); // 10
console.log(~x); // -11
console.log(x << 2); // 40
console.log(x >> 2); // 2
```
8) Ternary Operators

-They compare values and return a boolean value (true or false)

Example

```javascript
let x = 10;
let y = 5;
console.log(x > 5 ? "x is greater than 5" : "x is not greater than 5"); // x is greater than 5
``` 
9)Greater than or equal to

-It returns true if the value of the left operand is greater than or equal to the value of the right operand, and false otherwise.

Example

```javascript
let x = 10;
let y = 5;
console.log(x >= y); // true
console.log(x <= y); // false
```


## Logical Operators
- They are used to perform logical operations on values.

They include:

1) `&&` Logical AND operator

-It returns true if both operands are true, and false otherwise.

Example

```javascript
let x = 10;
let y = 5;
console.log(x > 5 && y < 10); // true
```
2) `||` Logical OR operator

-It returns true if at least one operand is true, and false otherwise.

Example

```javascript
let x = 10;
let y = 5;
console.log(x > 10 || y < 5); // false
```
3) `!` Logical NOT operator

-It returns true if the operand is false, and false otherwise.

Example

```javascript
let x = 10;
let y = 5;
console.log(!x); // false
console.log(!y); // true
```
4) `&&` Logical AND 

-The `&&` operator is used to perform logical AND operations on values.
- `&&` Logical AND

## Logical OR
-The `||` operator is used to perform logical OR operations on values.

Example

```javascript
let x = 10;
let y = 5;
console.log(x > 10 || y < 5); // false
```

