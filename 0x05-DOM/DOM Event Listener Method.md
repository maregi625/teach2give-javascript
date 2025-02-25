## DOM Event Listener an element.

- The `addEventListener()` method attaches an event handler to a specified element.

- It attaches an event handler without overwriting existing handlers.

- It takes in three parameters (for now let's focus on the first two).

- The first parameter is the type of event passed in as a string e.g., click, mousedown, mouseenter e.t.c.

- The second parameter is the function we want to call when the specified event occurs.

- The third parameter is a Boolean value that specifies whether to capture the event or not.

Example

```javascript
document.getElementById("myButton").addEventListener("click", myFunction, true);
console.log("The button was clicked");
```

## Event Propagation

- Event propagation is the process of how an event is passed from one element to another element.

- Event propagation is a way to handle events in a tree of elements. 

- There are two ways of even propagation:

1) Bubbling
- The event is passed from the child element to the parent element.

2) Capturing
- The event is passed from the parent element to the child element.

