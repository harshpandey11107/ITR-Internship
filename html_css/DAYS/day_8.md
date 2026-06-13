# Day 8 - JavaScript Arrays & Data Types

 10. Introduction to Arrays:-

### Array Destructuring

* Array Destructuring is a JavaScript feature.
* It allows extracting array values into separate variables.

```javascript
let fruits = ["Apple", "Banana"];
let [first, second] = fruits;

console.log(first);
console.log(second);
```

### Array Methods

* Array methods are built-in JavaScript functions.
* They are used to add, remove, search, and modify array elements.

Common Methods:

* push()
* pop()
* shift()
* unshift()

### Arrays

* Arrays are used to store multiple values in a single variable.

```javascript
let fruits = ["Apple", "Banana", "Mango"];

console.log(fruits);
```

### Clone Array

* Cloning an array means creating a copy of an existing array without changing the original array.
* The Spread Operator (`...`) is commonly used for cloning arrays.

```javascript
let arr1 = [1, 2, 3];
let arr2 = [...arr1];

console.log(arr2);
```

---

 11. Primitive & Reference:-

 Data Types:

* Data types define the kind of value a variable can store in JavaScript.

Common Data Types:

* Number
* String
* Boolean
* Undefined
* Null
* Object
* BigInt

```javascript
let name = "Chinmay";      // String
let isStudent = true;      // Boolean

console.log(name);
console.log(isStudent);
```

