1. What is JavaScrpt?

<details><summary>Show Answer</summary>
  
  - JavaScript is  the most commonly used **client side scripting langauge**. 
-  JS is *high-level*, *multi-paradign*, *interpreted* programming language.
   - used to create dynamic web pages(using DOM Manipulation).
- JS is dynamically and loosely typed.(Doesnt enforce type safety).
- Single thereaded(It runs using whats called an Event loop)
- Used in HTML
- Officialy called as ECMAScript
  
</details>

2. What are primitive data types in JavaScript?

<details><summary>Show Answer</summary>

  - Primitives
  - number
  - string
  - boolean
  - symbol
  - undefined
  - null
  - bigint
  
</details>

3. What are reference data types in JavaScript?

<details><summary>Show Answer</summary>

  - References (Objects)
  - Array
  - object
  
</details>

4. How do you declare a variable in JavaScript?


<details><summary>Show Answer</summary>
  
  In JavaScript, you can declare a variable using the var, let, or const keyword, followed by the variable name. The var keyword has function scope, while let and const have block scope.
  
  ```js
  var myVariable;
let anotherVariable;
const PI = 3.14;

```
  
</details>

5. How do you output data to the console in JavaScript?

<details><summary>Show Answer</summary>

You can use the console.log() function to output data to the console in JavaScript. It is commonly used for debugging and displaying information during development.
  
  ```js
  console.log("Hello, world!");
  
  ```
  
</details>

6. How do you write a conditional statement in JavaScript?

<details><summary>Show Answer</summary>
  
  JavaScript provides the if statement for conditional branching. It allows you to execute a block of code if a certain condition is true. Optionally, you can include else if and else clauses for additional conditions.
  
  ```js
  var age = 20;

if (age >= 18) {
  console.log("You are an adult.");
} else {
  console.log("You are a minor.");
}

  ```
  
</details>

7. How do you loop through an array in JavaScript?

<details><summary>Show Answer</summary>
  
  You can use a for loop to iterate through each element of an array in JavaScript. The loop variable can be used to access each element by its index.
  
  ```js
  var myArray = [1, 2, 3, 4, 5];

for (var i = 0; i < myArray.length; i++) {
  console.log(myArray[i]);
}

  ```
  
</details>

  8. How do you define a function in JavaScript?

<details><summary>Show Answer</summary>
  
  You can define a function in JavaScript using the function keyword, followed by the function name and a pair of parentheses. Any parameters are listed within the parentheses, and the function code is enclosed in curly braces.
  
  ```js
  
  function greet(name) {
  console.log("Hello, " + name + "!");
}

greet("Alice");

  
  ```
  
</details>
  
  9. What is the difference between let, const, and var in JavaScript?

<details><summary>Show Answer</summary>
  
  var: Variables declared with var have function scope and can be reassigned and redeclared within the same scope.
let: Variables declared with let have block scope and can be reassigned but not redeclared within the same scope.
const: Variables declared with const also have block scope, but their value cannot be reassigned once it is assigned.
  
  
</details>
  
  10. What is the purpose of the return statement in JavaScript?

 
<details><summary>Show Answer</summary>
  
  The return statement is used to end the execution of a function and specify the value to be returned by that function. It allows a function to send a value back to the code that called it, making it useful for returning results or data from a function.
  
</details>
