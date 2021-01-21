1. In code below "Mark" is a string. What is name?

```js
var name = "Mark"; //String
```

2. Find the error if any

```js
  var product cost = 3.45; //product cost
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" //right
  'Hello World"
  // wrong
  "Hello World'
  // wrong
  'Hello World'
  // wrong
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man;
// valid
var 1girl;
// invalid
var woman3;
// valid
var -girl;
// invalid
var blackDog;
// valid
var 42;
// invalid
var $42;
// invalid
var userName;
// valid
var x, y, z;
// valid
var x = 5, y = 6, z = 7;
// valid
var x = 5 + 10 + 2;
// valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var a = amount - 80;

// Define a new variable and store the value that is 200 more then the value of amount.
var b = amount + 200;

// Define a new variable and store the value that is 4 times the value of amount.
var c = 4 * amount;

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var d = amount % 21;
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark
console.log(johnAge > markAge ? "John" : "Mark");

// Check who is younger
console.log(johnAge < markAge ? "John" : "Mark");

// Check if their age is equal
console.log(johnAge == markAge);

// Create a new variable and assign the age of john to new variable.
var newAge = johnAge;

// Check if john is equal to or greater then mark.
console.log(johnAge == markAge || johnAge > markAge);

// Check if john is less then or equal to mark.
console.log(johnAge == markAge || johnAge < markAge);

// Calculate the average age of john and mark and assign to a new variable.
var avgAge = (johnAge + markAge) / 2;
```
