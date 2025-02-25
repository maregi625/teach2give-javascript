## DOM Events

- DOM events are events that occur in the Document Object Model (DOM).

- DOM events are triggered when an element is interacted with by the user.

## Some popular DOM events

 1) `onclick`

-It is triggered when the user clicks on an element.

Example

```html
<button onclick="myFunction()">Click me</button>
console.log("The button was clicked");
```

 2) `onmouseover`

- It is triggered when the user moves the mouse over an element.

Example

```html
<div onmouseover="myFunction()">Hover over me</div>
console.log("The mouse is over the div");
```

 3) `onmouseout`

- It is triggered when the user moves the mouse out of an element.

Example

```html
<div onmouseout="myFunction()">Hover over me</div>
console.log("The mouse is out of the div");
```

 4) `onkeydown`

- It is triggered when the user presses a key on the keyboard.

Example

```html
<input type="text" onkeydown="myFunction(event)">
console.log("The user pressed a key");
```

5) `onkeyup`

- It is triggered when the user releases a key on the keyboard.

Example

```html
<input type="text" onkeyup="myFunction(event)">
console.log("The user released a key");
```

6) `onload`

- It is triggered when the page is loaded.

Example

```html
<body onload="myFunction()">
console.log("The page was loaded");
```
7) `onfocus`

- It is triggered when the user clicks on an element.

Example

```html
<input type="text" onfocus="myFunction()">
console.log("The input field was focused");
```