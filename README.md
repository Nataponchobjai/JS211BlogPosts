Class 10: Prompt 205 - September 28
1. Describe one thing you're learning in class today. Why do you think it will be important in your future web development journey?
I leanred how to build my own unit tests. Building tests is important, because if you're working for a company with proprietary information, you don't want to just plug it in to codepen.io for the world to see just to be able to test your work.

2. Can you offer a use case for the new arrow => function syntax?
When storing a function in a const variable, so  const exampleFunction = (parameter) => {} 

3. How does this new syntax differ from the older function signature, function nameFunc(){}, both in style and functionality?
The arrow code is written as
const nameFunc = () => { // function body };
while the older function is written as
function nameFunc() {// function body} 
The arrow syntax is more advantageous because it's more concise (can be written all on one line),
// Arrow function
const add = (a, b) => a + b;

// Traditional function
function add(a, b) {
return a + b;
}
and also it inherit's the this binding, unlike the older syntax where you have to define the function along with this for the binding to work.

4. Explain the differences on the usage of foo between function foo() {} and const foo = function() {}
The first one is creating a function called foo and the second is creating a variable called foo that will contain a function.

5. What advantage is there for using the arrow syntax for a method in a constructor?
With arrow functions, you can define methods inside the constructor itself, and you can still use the `this` binding with them.

6.Can you give an example for destructuring an object or an array?
const person = {
  name: "Alice",
  age: 30,
  city: "New York"
};

// Destructuring the object
const { name, age, city } = person;

7.Explain Closure in your own words. How do you think you can use it? Don't forget to read more blogs and videos about this subject.
To first understand Closure it's important to understand "lexical scope". Lexical scope basically means the scope of a variable is determined by its position within the source code. Like a variable defined within a function will not operate the same way as a variable defined outside of a function. A closure is a mix of a function and the lexical scope within which that function was declared. It's basically when you declare the function one last time.
