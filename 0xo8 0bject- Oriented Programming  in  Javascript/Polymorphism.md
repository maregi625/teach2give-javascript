## Polymorphism

- Polymorphism is a concept in object-oriented programming that allows objects of different classes to be treated as instances of a common base class.

- Polymorphism allows you to write code that can work with objects of different classes without knowing the specific class of the object.

Example

```javascript
class Math {
  add(number1, number2) {
    return number1 + number2;
  }
}

class Arithmetics extends Math {
  add(number1, number2) {
    if (number1 < 0) {
      console.log("Can only add positive numbers");
    } else if (number2 < 0) {
      console.log("Can only add positive numbers");
    } else {
      console.log(number1 + number2);
    }
  }
}

const arithmetic = new Arithmetics();
arithmetic.add(-5, 5);
arithmetic.add(5, -5);
arithmetic.add(5, 5);
```
