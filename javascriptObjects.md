## **Objects and its internal representation in javascript**

Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

**Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.**

objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of **“key: value” pairs.** These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.

``````
// Creating an object
let car = {
    brand: "Toyota",
    model: "Camry",
    year: 2022,
    
};

// Accessing properties
console.log(car.brand); // Outputs: Toyota

// Adding a new property dynamically
car.color = "Blue";


Using the JavaScript Keyword new
var person = new Object();
person.firstName = “abcd”;
person.lastName = “xyz”;
person.age = 60;
person.eyeColor = “blue”;

```````