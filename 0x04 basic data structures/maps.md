## Maps

- A map is a collection of key-value pairs.

- Maps are used to store data in a structured way.

- Maps are used to represent real-world entities.

## Creating a map

- A map can be created using the `new Map()` constructor.

Example

```javascript
const myMap = new Map();
```

## Map methods


<h1>set (key, value)</hi>



- Adds a key value pair to the map or updates if the key-value pair already exists.

Example

```javascript
const myMap = new Map();
myMap.set("name", "nderi");
myMap.set("age", 30);
myMap.set("city", "Nairobi");
console.log(myMap); // Map(3) {"name" => "nderi", "age" => 30, "city" => "Nairobi"}
```

<h1>get (key)</hi>

- Returns the value associated with the given key.

Example

```javascript
const myMap = new Map();
myMap.set("name", "nderi");
myMap.set("age", 30);
myMap.set("city", "Nairobi");
console.log(myMap.get("name")); // nderi
``` 

<h1>has (key)</hi>

- Returns true if the map contains the given key.

Example

```javascript
const myMap = new Map();
myMap.set("name", "nderi");
myMap.set("age", 30);
myMap.set("city", "Nairobi");
console.log(myMap.has("name")); // true
```

<h1>delete (key)</hi>

- Removes the key-value pair associated with the given key.

Example

```javascript
const myMap = new Map();
myMap.set("name", "nderi");
myMap.set("age", 30);
myMap.set("city", "Nairobi");
myMap.delete("age");
console.log(myMap); // Map(2) {"name" => "nderi", "city" => "Nairobi"}
```

<h1>clear ()</hi>

- Removes all key-value pairs from the map.

Example

```javascript
const myMap = new Map();
myMap.set("name", "nderi");
myMap.set("age", 30);
myMap.set("city", "Nairobi");
myMap.clear();
console.log(myMap); // Map(0) {}
```

<h1>size</hi>

- Returns the number of key-value pairs in the map.

Example

```javascript
const myMap = new Map();
myMap.set("name", "nderi");
myMap.set("age", 30);
myMap.set("city", "Nairobi");
console.log(myMap.size); // 3
```







 
















