## Accessing Dom Elements

- To access a DOM element, you can use the `document.getElementById()` method.

## Methods For Accessing Dom Elements

- The `document.getElementById()` method returns the element with the specified ID.

1) `document.getElementsByClassName()`
- It finds an element with id equivalent to `elementId`.

Example

```javascript
const element = document.getElementById("myElement");
```

2) `document.getElementsByTagName()`

- Finds all the elements that match the tag name passed, e.g., finding all paragraph elements in a page.

- It returns a NodeList of all elements that match the tag name passed.

- You can index the specific element you want from this element the same way you would index an array.

Example

```javascript
const elements = document.getElementsByTagName("p");
```

3) `document.querySelector()`

- It returns the first element that matches the specified CSS selector.

Example

```javascript
const element = document.querySelector("#myElement");
```




