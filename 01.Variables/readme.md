### Variables and Strings
    1. Variable basics with var.
    2. Better code with strict mode.
    3. Why use let & const over var.
    4. Why blocking scope matters.
    5. How template literals improve strings.
    6. How variables should be named.

## Rules for naming variables
 1) names only contain letters, numbers, symbol ($ , _)(Only these two symbols are valid in variable names).
 2) first character must not be a number.


Global object is an object which can be accessed from anywhere in the application.
Javascript runs on various environments(browser/server)
 Javascript can either run in window or on server.
 Javascript can run in either of the following modes:
 1) sloppy "normal" mode - default in scripts
 2) strict mode - throws more errors, prevents pitfalls of the language

## Hoisting
This code in sample 1 and sample 2 will run as it is i.e hoisting is defined as the Javascript engine declaring the variable at the beginning of the program/scope even if it declared at the last by the user
var age;
console.log(age); // undefined
age = 26;