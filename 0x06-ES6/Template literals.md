## Template Literals

- Template literals are a new way to write strings in JavaScript.
- They allow:
    - Multiline strings
    - String interpolation
    - String escaping
    - String substitution
    - embedded expressions
    - e.t.c


   ## String Interpolation:Injecting variables into strings

   - Template literals can be used to inject variables into strings.
   - This is known as string interpolation.

   Example

   ```javascript
   const name = "Nderi";
   const age = 30;
   const message = `My name is ${name} and I am ${age} years old.`;
   console.log(message); // Output: My name is Nderi and I am 30 years old. 
   ```

   ## Multi-line Strings

   - Template literals can be used to create multi-line strings.
   - This is known as multi-line strings.

   Example

   ```javascript
   const message = `
   This is a multi-line string.
   It can span multiple lines.
   `;
   console.log(message); // Output: This is a multi-line string. It can span multiple lines.
   ```
   ## Expressions inside template literals

   - Template literals can evaluate expressions inside them.

   Example

   ```javascript
   const name = "Nderi";
   const age = 30;
   const message = `My name is ${name} and I am ${age} years old.`;
   console.log(message); // Output: My name is Nderi and I am 30 years old.
   ```

