# JavaScript Statements

```js
let x, y, z;    // Statement 1
x = 5;          // Statement 2
y = 6;          // Statement 3
z = x + y;      // Statement 4
```

## JavaScript Programs

- a computer program is a list of instructions to be executed by a computer
- programming instructions are called `statements`
- a JavaScript program is a list of programming statements

### JavaScript Statements

- composed of:
    - Values
    - Operators
    - Expressions
    - Keywords
    - Comments

This statement tells the browser to write "Hello, Dolly." inside the HTML element with id="demo":

```js
document.getElementById("demo").innerHTML = "Hello, Dolly.";
```

- most JavaScript programs contain many statements
- the statements are executed one by one in the same order as they are written
- JavaScript programs/statements are often called JavaScript code

### Semicolons

- `;` are used to separate JS statements
- add a `;` after each executable statement

```js
let a, b, c;  // Declare 3 variables
a = 5;        // Assign the value 5 to a
b = 6;        // Assign the value 6 to b
c = a + b;    // Assign the sum of a and b to c
```

- multiple statements are allowed on one line when separated by semicolons:

```js
a = 5; b = 6; c = a + b;
```

- ending statements without a semicolon is not required, but **highly recommended**

## JavaScript White Space

- JS ignores white space
- you can add white space to your script to make it more readable

These lines are equivalent:
```js
let person = "Hege";
let person="Hege";
```

It's good practice to put spaces around operators ( = + - * /):

```js
let x = y + z;
```

## JavaScript Line Length and Line Breaks

- for readability, programmers like to avoid code lines longer than 80 characters
- If a JavaScript statement doesn't fit on one like, best place to break it is after an operator:

```js
document.getElementById("demo").innerHTML =
"Hello Dolly!";
```

## JavaScript Code Blocks

- JavaScript statements can be grouped together in `code blocks` in curly brackets `{}`
- the purpose of code blocks is to group statements executed together
- one place you will find statements grouped in blocks is JavaScript functions

```js
function myFunction() {
  document.getElementById("demo1").innerHTML = "Hello Dolly!";
  document.getElementById("demo2").innerHTML = "How are you?";
}
```

## JavaScript Keywords

- JS statements often start with a keyword to identify the JS action to be performed
- List of all JS keywords: 
https://www.w3schools.com/js/js_reserved.asp
- some keywords you will learn about in this tutorial:

| Keyword | Description |
|---|---|
|var|	Declares a variable|
|let|	Declares a block variable|
|const|	Declares a block constant|
|if|	Marks a block of statements to be executed on a condition|
|switch|	Marks a block of statements to be executed in different cases|
|for|	Marks a block of statements to be executed in a loop|
|function|	Declares a function|
|return|	Exits a function|
|try|	Implements error handling to a block of statements|


