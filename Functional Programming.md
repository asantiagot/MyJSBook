# Functional Programming
Functions can be sent to functions as arguments or returned from functions as results. More complex functions, called higher-order-functions, can manipulate functions and use them as either arguments or results or both. 

## First-class members / first-class citizens
A function is considered a first-class member when it can be declared as a variable and sent to functions as an argument. These functions can even be returned from functions.

## JS Functional Programming
JS supports functional programming because JavaScript functions are first-class citizens. Functions can do the same things that variables can do. 

    var log = function(message) {
        console.log(message);
    };
