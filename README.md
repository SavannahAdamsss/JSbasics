# JSbasics
Definitions and Explanations for the Basics:

DOM Stuff:

* // Getting the element with the given id
// There will be only one
let title = document.getElementById('title');
title = document.getElementsByClassName('title')[0];
title = document.getElementsByTagName('h1')[0];
title = document.getElementsByName('title')[0];
title = document.querySelector('#title'); // any valid css selector
title = document.querySelectorAll('h1')[0];  // any valid css selector



* A variable is a way to store a data type for later use in your program. Variables have names!
* Define an API
    * Application Programming Interface
        * DOM
    * Web API - an API accessible over the HTTP protocol 
        * Over the internet
        * Typically has a database behind the scenes
* List many commonly used Web APIs
    * Weather
    * Facebook, Twitter, Reddit, Google Maps
    * Dictionary
    * Government Data, Census
* Read the docs of an API
* Make a request to an API with Postman
* To make a request with JS use fetch


* BUCKET TWO PROJECT REQUIREMENTS:
* NO Authentification
* Does it require an API key? If so, request it now!!
* Does it support CORS?
* Can I request it from Postman?


* Define the following words and give at least 3 examples of each:
    1. Value
      * The thing itself 
    2. Expression
      * Can be evaluated
      * 'asdf' + someVariable
    3. Statement
      * A line of code not in brackets
      * A variable definition
      * Block of code
    4. Identifier
      * A variable name
    5. Keyword
      * Reserved word:
      * function, var, let, const, if, else, for, ..
    6. Operator
      * +, =, +=, >, <, /, ==, ===, new, &&, ||
    7. Literal
      * {}, a number like 42, 'bob', []
      * {} is the same thing as let obj = new Object()
    8. Assign
      * Give a variable a value
      * This is the step after "declare", you can't use let in it
    9. Declare
      * Define a variable like 'let result'
    10. Evaluation
      * "runs the code"
      * An expression that can be further processed to create a single value
* Label all of the parts of the following JavaScript statement:
```js
  let x = 1 + 1;


  // 1. Declare a variable called x, assign the value 42 to x
    let x = 42;

// 2. Log the identifier x
    console.log(x);

// 3. Declare a variable called y, assign the variable y the expression of two literal values of 1 added together
    let y = 1 + 1; 

// 4. Write a statement that declares a variable called happy, assign the variable the literal value true
    let happy = true;

// 5. Define a variable called days, assign the literal value 5 to it
    let days = 5;

// 6. Define a variable called hoursPerDay, assign the literal value 8 to it
    let hoursPerDay = 8;    

// 7. Define a variable called rate, assign the literal value 35.50 to it
    let rate = 35.50;

// 8. Define a variable called pay, assign the multiplication of the days, hoursPerDay and rate identifiers to the pay identifier
    let pay = days * hoursPerDay * rate;

// 9. Log the pay identifier
    console.log(pay)

// 10. Say all of the code above out loud, using vocab words, without reading the comments.