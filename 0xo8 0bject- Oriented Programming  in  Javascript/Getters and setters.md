## getters and Setters
- Getters and Setters are special methods that allow controlled access to an object's properties.

-They enable data encapsulation by restricting direct access and enforcing validation.

- Getters `(get)`: retrieve a property value.

- Setters `(set)`: modifies a property value while allowing validation.

Example of a class without getters and setters:

```javascript
class User {
  constructor(name) {
    this.name = name; // Direct access
  }
}

const user = new User("Dennis");
console.log(user.name); // "Dennis"

user.name = 42; // No validation, allows invalid data
console.log(user.name); // 42 (Not ideal)
```