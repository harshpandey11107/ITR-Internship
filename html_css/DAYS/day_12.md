# Day 12 – JavaScript Functions

1. Introduction to Functions
A function is a reusable block of code that performs a specific task. It runs only when called.
Example:
JavaScript
function greet() {
    console.log("Hello");
}

greet();

2. Function Declaration
A function declared using the function keyword. It is hoisted, so it can be called before its declaration.
Example:
JavaScript
function add(a, b) {
    return a + b;
}

console.log(add(5, 3));

3. Function Expression
A function stored inside a variable. It is not hoisted like a function declaration.
Example:
JavaScript
const greet = function () {
    console.log("Hello");
};

greet();

4. Arrow Functions
Arrow functions provide a shorter syntax for writing functions.
Example:
JavaScript
const add = (a, b) => a + b;

console.log(add(2, 3));

5. Callback Functions
A callback is a function passed as an argument to another function and executed later.
Example:
JavaScript
function greet(name) {
    console.log("Hello " + name);
}

function process(callback) {
    callback("Chinmay");
}

process(greet);

6. Default Parameters
Default parameters assign a default value if no argument is passed.
Example:
JavaScript
function greet(name = "Guest") {
    console.log(name);
}

greet();

7. Rest Parameters
Rest parameters (...) allow a function to accept multiple arguments as an array.
Example:
JavaScript
function sum(...numbers) {
    console.log(numbers);
}

sum(10, 20, 30);

8. Hoisting
Hoisting in JavaScript is the behavior of moving function declarations and variable declarations to the top of their scope before execution.
Example:
JavaScript
sayHello();

function sayHello() {
    console.log("Hello");
}

9. Lexical Scope
An inner function can access variables from its outer function.
Example:
JavaScript
function outer() {
    let name = "Chinmay";

    function inner() {
        console.log(name);
    }

    inner();
}

outer();

10. Block Scope vs Function Scope
let and const are block-scoped.
var is function-scoped.
Example:
JavaScript
{
    let a = 10;
    const b = 20;
}

var c = 30;
console.log(c);