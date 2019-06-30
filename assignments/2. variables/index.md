1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark"; // name is a string; 
```

2. Find the error if any
```js
  var product cost = 3.45; 
  
  var productcost = 3.45; //removed space between product and cost.
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" : Right;
  'Hello World" : Wrong;  // different "/' used
  "Hello World' : Wrong;  // different "/' used
  'Hello World' : Right;
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; //valid
var 1girl; //invalid (variables cant with numbers)
var woman3; //valid
var -girl; //invalid (- cannot be used. Only $ and _)
var blackDog; //valid
var 42; //invalid
var $42; //valid
var userName; //valid
var x, y, z; //valid
var x = 5, y = 6, z = 7; //valid
var x = 5 + 10 + 2;  //valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.

var amount = 2080;
var lessEighty = amount - 80
// Define a new variable and store the value that is 200 more then the value of amount.

var amount = 2080;
var more200 = amount + 200;
// Define a new variable and store the value that is 4 times the value of amount.
var amount = 2080;
var multiplyfour = amount * 4;
// Define a new variable and store the reminder when the value of amount is  divided by 21.

var amount = 2080;
var divide21 = amount / 21;
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark

johnAge  > markAge //true, John is elder

// Check who is younger

johnAge < markAge //false, john is not younger, hence Mark is.

// Check if their age is equal

johnAge == markAge //false

// Create a new variable and assign the age of john to new variable.

var newJohnAge = johnAge;

// Check if john is equal to or greater then mark.

newJohnAge >= markAge // True

// Check if john is less then or equal to mark.

newJohnAge <= markAge // False

// Calculate the average age of john and mark and assign to a new variable.

// var averageAge: (newJohnAge + markAge) / 2; 
//unexpected token error
```