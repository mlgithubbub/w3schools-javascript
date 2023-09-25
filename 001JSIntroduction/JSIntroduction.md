# JavaScript Introduction

## JavaScript Can Change HTML Content

- `getElementById()` is one of the many JavaScript HTML methods
- This example finds the HTML element with id="demo" and changed the element content (innerHTML) to "Hello JavaScript":

```js
document.getElementById("demo").innerHTML = "Hello JavaScript";
```
JavaScript accepts both single and double quotes:

```js
document.getElementById('demo').innerHTML = 'Hello JavaScript';
```

## JavaScript Can Change HTML Attribute Values

- In this example JavaScript changes the `src` attribute of an `<img>` tag:
```html
<button onclick="document.getElementById('myImage').src='pic_bulbon.gif'">Turn on the light</button>

<img id="myImage" src="pic_bulboff.gif" style="width:100px">

<button onclick="document.getElementById('myImage').src='pic_bulboff.gif'">Turn off the light</button>
```

## JavaScript Can Change HTML Styles (CSS)

- In this example, JavaScript changes the style of an HTML element:

```js
document.getElementById("demo").style.fontSize = "35px";
```

## JavaScript Can Hide HTML Elements

- JavaScript can change the `display` style and hide an HTML element:

```js
document.getElementById("demo").style.display = "none";
```

## JavaScript Can Show HTML Elements

- JavaScript can change the `display` style and show an HTML element:

```js
document.getElementById("demo").style.display = "block";
```

## Did You Know?

- JavaScript and Java are completely different languages in concept and design
- JavaScript was invented by Brendan Eich in 1995
- JavaScript became an ECMA standard in 1997
- ECMA-262 is the official name of the standard
- ECMAScript is the official name of the language


