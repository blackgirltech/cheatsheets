# JavaScript Cheat Sheet

## Variables
```js
// Declare variables using 'var' and 'let'
var today = "Friday";
let coldOutside = true;

// Declaring a constant - a variable you don't want to be changed
const daysInAWeek = 7;
```

## Linking to a JS file in your `index.html`
```html
<!DOCTYPE html>
<html>
  <body>
    <h1>My web page</h1>

    <!-- insert script last to avoid delaying page load -->
    <script src="javascript.js"></script>
  </body>
```

## Functions
```js
// Declare a function that logs a greeting
function greetPerson (person) {
  console.log('Hello' + person)
}

// Call function with a name
greetPerson('Temi') // 'Hello Temi'
```
