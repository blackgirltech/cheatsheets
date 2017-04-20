# JavaScript Cheat Sheet

## Linking to a JS file in your `index.html`
```html
<!DOCTYPE html>
<html>
  <body>
    <h1>My web page</h1>

    <!-- insert script last to avoid delaying page load -->
    <script src="javascript.js"></script>
  </body>
</html>
```

## Value types
- Booleans: `true`, `false`
- Numbers: `20`, `3.14`
- Strings: `'This is a string'`, `"This is also a string"`

## Variables
```js
// Declare variables using 'var' and 'let'
var today = "Friday";
let coldOutside = true;

// Declaring a constant - a variable you don't want to be changed
const daysInAWeek = 7;
```

## Functions
```js
// Declare a function that logs a greeting
function greetPerson (person) {
  console.log('Hello' + person);
}

// Call function with a name
greetPerson('Temi'); // 'Hello Temi'
```

## `if` statements
```js
let degrees = 8;

// Wear a jacket depending on the weather
if (degrees > 15) {
  console.log('No need for a jacket')
} else {
  console.log('You'd better have your jacket')
}
```

## Arrays
```js
// Create an array of numbers
const myNumbers = [1, 2, 3];

// Iterate over array and log each number
myNumbers.forEach(function(number) {
  console.log(number); // 1, 2, 3
})
```

## Objects
```js
// Create an empty object
let myObj = {};

// Add data to the object
myObj.job = 'Developer';

// See what's inside
console.log(myObj); // { job: "Developer" }
```
