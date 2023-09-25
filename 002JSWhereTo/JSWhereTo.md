# JavaScript Where To

## The `<script>` Tag

- in JavaScript, code is inserted between `<script>` and `</script>` tags

```html
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
```

- NOTE: Old JavaScript examples might use a `type` attribute:
```html
<script type="text/javascript">
```
This is not necessary because JavaScript is the default scripting language in HTML

## JavaScript Functions and Events

- a `function` is a block of JavaScript code that can be executed when "called" for
- for example, a function can be called when an `event` occurs such as clicking on a button

## JavaScript in `<head>` or `<body>`

- you can place as many scripts as you want in an HTML document
- scripts can be placed in the `<head>` section, `<body>` section, or both

## JavaScript in `<head>`

- In this example, a JavaScript function is placed in the `<head>` section of an HTML page
- The function is invoked/called when a button is clicked:
```html
<!DOCTYPE html>
<html>
<head>
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head>
<body>
<h2>Demo JavaScript in Head</h2>

<p id="demo">A Paragraph</p>
<button type="button" onclick="myFunction()">Try it</button>

</body>
</html>
```

## JavaScript in `<body>`

- In this example, a JavaScript function is placed in the `<body>` section of an HTML page
- The function is invoked/called when a button is clicked:
```html
<!DOCTYPE html>
<html>
<body>

<h2>Demo JavaScript in Body</h2>

<p id="demo">A Paragraph</p>

<button type="button" onclick="myFunction()">Try it</button>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>

</body>
</html>
```

## External JavaScript

- scripts can also be placed in external files

myScript.js
```js
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
```
- external scripts are practical when same code is used in many different web pages
- JavaScript files have the extension .js
- to use an external script, put the name of the script file in the `src` attribute of a `<script>` tag

```html
<script src="myScript.js"></script>
```
- you can put an external script reference in the `<head>` or `<body>`
- the script behaves just as though it were where the `<script>` tag is located in the html
- external scripts cannot contain `<script>` tags

## External JavaScript Advantages

- separates HTML and code
- makes HTML and JavaScript easier to read and maintain
- Cached JavaScript files can speed up page loads

Use several script tags to add several script files to one page:
```html
<script src="myScript1.js"></script>
<script src="myScript2.js"></script>
```

## External References

- external scripts can be referenced in 3 ways:
    - full URL: full web address
    ```html
    <script src="https://www.w3schools.com/js/myScript.js"></script>
    ```
    - with file path
    ```html
    <script src="/js/myScript.js"></script>
    ```
    - without any path
    ```html
    <script src="myScript.js"></script>
    ```



