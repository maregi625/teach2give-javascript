# INTRODUCING JAVASCRIPT IN HTML
There are two ways to include js in html
## A. Internal
the `<script>` tag is placed within the  `<body>` element  of html file

example
```html 
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>JavaScript</h1>
    <script> 
      console.log("Hello, world!");
      console.log("Am learning Javascript")
    </script>
  </body>
</html>

```


Point to note

The script must be at the end of the body element


## B. Extrernal
Javascriot is stored in a "js" file and linked to the HTML document using the `<script>` tag and a src attribute

example

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script src="app.js"></script>
  </head>
  <body>
    <h1>JavaScript</h1>
  </body>
</html>

```

### Optimizing script loading
Javascript can block page rendering if not correctly loaded but when it comes into contact with the script tags to  download Javascript, it stops until the Javascript has been downloaded.

To improve it's performance one can use; 

1.Defer keyword
-it ensures scripts are loaded after the HTML is fully loaded

Example
```html
<script src="app.js" defer></script

```

2.Async keyword
-it ensures scripts are loaded after the HTML is fully loaded

Example
```html
<script src="app.js" async></script

```
3.The script tag at the end of the body element-
-it ensures scripts are loaded after the HTML is fully loaded
Example

```html
...
    <script src="app.js"></script>
</body>
</html>

``` 
Note better

Before putting the script at the end of the body element, it is better to put the script at the top of the body element.