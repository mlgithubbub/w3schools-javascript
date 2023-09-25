# JavaScript Syntax

- the set of rules governing how JS programs are constructed:
```js
// How to create variables:
var x;
let y;

// How to use variables:
x = 5;
y = 6;
let z = x + y;
```

## JavaScript Values

- JS syntax defines two types of values:
    1. `literals`: fixed values
    2. `variables`: variable values

### JavaScript Literals

- Two most important rules:
    1. numbers are written with or without decimals:
    ```
    10.50
    1001
    ```
    2. strings are text written within double or single quotes:
    ```
    "John Doe"
    'John Doe'
    ```

## JavaScript Variables

- `variables` are used to store data values
- use keywords `var`, `let` and const to declare variables
- `=` equal sign is used to assign values to variables

In this example, x is defines as a variable, then x is assigned the value of 6:

```js
let x;
x = 6;
```

## JavaScript Operators

- `arithmetic operators`: + - * /, used to compute values:
```js
(5 + 6) * 10
```
- `assignment operator`: =, used to assign values to variables:
```js
let x, y;
x = 5;
y = 6;
```

## JavaScript Expressions

- combination of values, variables, operators which computes to a value
- the computation is called an `evaluation`
- 5 * 10 `evaluates` to 50:

```js
5 * 10
```
- expressions can also contain variable values:
```js
x * 10
```
- values can be of various types, such as number and strings:
```js
"John" + " " + "Doe"
```

## JavaScript Keywords

- used to identify actions to be performed
- `let` keyword tells the browser to create variables:
```js
let x, y;
x = 5 + 6;
y = x * 10;
```
- `var` keyword also tell browser to create variables
```js
var x, y;
x = 5 + 6;
y = x * 10;
```

## JavaScript Comments

- comments are code after `//` or between `/*` and `*/`
- they are ignored, not executed

```js
let x = 5;   // I will be executed

// x = 6;   I will NOT be executed
```

## JavaScript Identifiers/Names

- `identifiers` are JS names
- identifiers are used to name: variables, keywords and functions
- JS name must begin with one of these:
    - a letter, capital or lower-case
    - a dollar sign
    - an underscore
- subsequent characters can be: letters, digits, underscores, dollar signs
- numbers are not allowed as the first character in names!

## JavaScript is Case Sensitive

- all JS identifiers are case sensitive
- variables `lastName` and `lastname` are two different variables:

```js
let lastname, lastName;
lastName = "Doe";
lastname = "Peterson";
```

## JavaScript and Camel Case

Historically, programmers have different ways of joining multiple words into one variable name:
 | Way | Example | JS |
 | --- | --- | ---|
 | hyphens | first-name | hyphens are not allowed in JS
 | underscore | first_name | |
 | upper camel case (Pascal case) | FirstName | |
 | lower camel case (Pascal case) | firstName | JS programmers usually use lower camel case |


## JavaScript Character Set

- uses the `unicode` character set: https://www.w3schools.com/charsets/ref_html_utf8.asp



