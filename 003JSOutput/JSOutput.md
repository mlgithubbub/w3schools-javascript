# JavaScript Output

## JavaScript Display Possibilities

JavaScript can "display" data in different ways:

1. writing inside of an HTML element: `innerHTML`
2. writing into HTML output using: `document.write()`
3. writing into an alert box using: `window.alert()`
4. writing into the browser console using: `console.log()`

### Using innerHTML

- to access an HTML element, JS can use `document.getElementById()` method
- `id` attribute defines the HTML element
- `innerHTML` property defines the HTML content

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My First Paragraph</p>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = 5 + 6;
</script>

</body>
</html>
```

### Using document.write()

- convenient for testing purposes
```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<script>
document.write(5 + 6);
</script>

</body>
</html>
```

- using document.write() after and HTML document is loaded will delete all existing HTML:

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<button type="button" onclick="document.write(5 + 6)">Try it</button>

</body>
</html>
```
- `document.write()` should only be used for testing!

### Using window.alert()

- use an alert box to display data:
```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<script>
window.alert(5 + 6);
</script>

</body>
</html>
```

- `window` is a global scope object (variable, properties and methods belong to the window object by default), so the window keyword is optional:
```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>
<p>My first paragraph.</p>

<script>
alert(5 + 6);
</script>

</body>
</html>
```

### Using console.log()

- good for debugging
```html
<!DOCTYPE html>
<html>
<body>

<script>
console.log(5 + 6);
</script>

</body>
</html>
```

### JavaScript Print

- JS has no print object or print methods
- you can't access output devices with JS
- only exception is calling the `window.print()` method in the browser to print the content of the current window:
```html
<!DOCTYPE html>
<html>
<body>

<button onclick="window.print()">Print this page</button>

</body>
</html>
```






