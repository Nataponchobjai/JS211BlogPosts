Class 10: Prompt 205 - September 28

What is different from function foo() {} and const foo = Function() {}?
Declaration and Hoisting:
function foo() {}: You can call the function before it's defined because it's hoisted. const foo = function() {}: You can't call the function before it's defined because only the declaration is hoisted, not the initialization.

Reassignment:
function foo() {}: Can't be reassigned but can be redeclared in the same scope. const foo = function() {}: Can't be reassigned because it's using const.
2.example for destructuring an object or an array?
const person = {
name: "Natapon",
age: 33,
city: "Austin"  
};
// Destructuring the object
const { name, age, city } = person;
