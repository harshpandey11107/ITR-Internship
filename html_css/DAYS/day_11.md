# Day 11 – JavaScript DOM



1. createElement() in JavaScript
The createElement() method is used to create a new HTML element dynamically using JavaScript.

Example:

let para = document.createElement("p");
para.innerText = "Hello World";
document.body.appendChild(para);

Output:
A new paragraph containing "Hello World" is added to the webpage.

2. Change Background Color
The style.backgroundColor property is used to change the background color of an HTML element.

Example:

document.body.style.backgroundColor = "lightblue";

Output:
The webpage background changes to light blue.

3. filter() Method
The filter() method creates a new array containing only the elements that satisfy a condition.

Example:

let fruits = ["Apple", "Banana", "Mango", "Orange"];
let result = fruits.filter(fruit => fruit.startsWith("A"));

console.log(result);

Output:

["Apple"]

4. Responsive Navbar
A responsive navbar automatically adjusts according to different screen sizes.

Example:

function toggleMenu() {
    document.getElementById("menu").classList.toggle("active");
}

