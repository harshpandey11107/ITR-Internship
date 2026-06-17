
# Day 10 - JavaScript DOM Manipulation & Traversing

 1. DOM.js

The DOM (Document Object Model) allows JavaScript to access and manipulate HTML elements. Using DOM methods, JavaScript can dynamically change content, styles, attributes, and respond to user actions.

 Example:
```javascript
const heading = document.getElementById("title");
heading.textContent = "Welcome to JavaScript";
````

This code selects an HTML element with the ID `title` and changes its text content.

--

 2. getElementById()

* Selects an element using its unique ID.
* One of the most commonly used DOM methods.

 Example:

```javascript
const element = document.getElementById("demo");
console.log(element);
```



 3. querySelector() and querySelectorAll()

* `querySelector()` selects the first matching element.
* `querySelectorAll()` selects all matching elements.

 Example:

```javascript
const firstPara = document.querySelector("p");
const allParas = document.querySelectorAll("p");
```


 4. getElementsByClassName() and getElementsByTagName()

* Select elements by class name.
* Select elements by HTML tag name.

 Example:

```javascript
const items = document.getElementsByClassName("item");
const paragraphs = document.getElementsByTagName("p");
```



 5. Changing Styles with JavaScript

JavaScript can modify CSS properties dynamically using the `style` property.

 Example:

```javascript
const box = document.getElementById("box");
box.style.backgroundColor = "blue";
box.style.color = "white";
```



 6. Iterating Through Elements

Multiple elements can be accessed and processed using loops such as `forEach()` and `for...of`.

 Example:

```javascript
const items = document.querySelectorAll(".item");

items.forEach(item => {
    console.log(item.textContent);
});
```



 7. DOM Traversing

DOM Traversing is the process of navigating between elements in the DOM tree.

Common properties:

* `parentElement`
* `children`
* `firstElementChild`
* `lastElementChild`
* `nextElementSibling`
* `previousElementSibling`

 Example:

```javascript
const parent = document.getElementById("container");
console.log(parent.children);
```

This code accesses all child elements inside the element with ID `container`.



 8. DOM Tree

A DOM Tree is a hierarchical representation of an HTML document. Every HTML element, attribute, and text is represented as a node.

JavaScript uses this structure to access and manipulate webpage content dynamically.

 Example:

```javascript
const body = document.body;
console.log(body.children);
```

This code accesses the `<body>` element and displays its child elements from the DOM tree.


