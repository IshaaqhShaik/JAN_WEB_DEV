# JAN_WEB_DEV

Class - 1: Git Theory

    What is Git

    Git Lifecycle.

    Recording changes to the repository

    what is Remote and Local respository

    what is meant by staging changes?

    Installation of the Git on various Operating Systems.

    Task: Prepare a practical cheatsheet of workflow's on Git Life cycle, Recording changes to repository,

Class - 2: Git Practical

    Git Commands:
        git add filename.txt, git status, git add ., git commit -m "commit message", git push

    Git branches:
        git branch, git checkout ., git checkout branch_name, git checkout -b branch_name,

    Topics:

        Feature branch workflow

        Importance of using branching

        git add . vs  git add filename, git checkout -b vs git checkout branch vs git checkout .,

    Task: Getting handson with the commands discussed.

    Create a branch from main in the local repo and  add the changes.

Class - 3: Git Advanced practical

    Git Commands:
        git fetch, git stash, git pop, git pull, git merge, git rebase, git log.

    Topics:
        git Rebase vs git Merge, git Pull vs git fetch.

Class - 4:

    Git Commands:
        git revert, git reset.

    Topics:

        Revert changes from various life cycles locally and remote.





Day 1: Basics of Programming
Variables:

What are variables?
Variables are containers for storing data values. They are named memory locations that hold values which can be changed during the program execution.
Variable Declarations and Definition

Declaration: let x;
Definition: let x = 5;
let vs const vs var

let: Block-scoped variable.
const: Constant, can't be reassigned.
var: Function-scoped variable (avoid using it due to global scope issues).
Data Types-1 (Number, Boolean, String)
Number: Represents numeric values.
Boolean: Represents true or false.
String: Represents textual data.

Day 2: Operators
Arithmetic Operators
+, -, *, /, %
Assignment Operators
=, +=, -=, *=, /=
Comparison Operators
==, ===, !=, !==, <, >, <=, >=
String Operators
Concatenation: 'Hello' + ' ' + 'World'
Primitive Conversions
Implicit conversion: 1 + '2' results in '12'.
Logical Operators
&&, ||, !

Day 4: Conditionals
Interaction (alert, prompt)
alert('Hello!');
let name = prompt('Enter your name:');
IF condition
javascript
if (condition) {
  // code to execute if the condition is true
}
if-else condition
javascript
if (condition) {
  // code to execute if the condition is true
} else {
  // code to execute if the condition is false
}
Nested if-else and else if
javascript
if (condition1) {
  // code to execute if condition1 is true
} else if (condition2) {
  // code to execute if condition2 is true
} else {
  // code to execute if none of the conditions are true
}
switch-case
javascript
switch (expression) {
  case value1:
    // code to execute if expression === value1
    break;
  case value2:
    // code to execute if expression === value2
    break;
  default:
    // code to execute if none of the cases match
}
Ternary Conditions
javascript
let result = (condition) ? 'true' : 'false';
Data Types-2 (NaN, Undefined, Null)
NaN: Not-a-Number.
Undefined: Default value of uninitialized variables.
Null: Represents the absence of any object value.

Day 5: Data Types-3 (Arrays and Objects)
Arrays
Containers for storing multiple values.
javascript
let numbers = [1, 2, 3];
let names = ['Alice', 'Bob', 'Charlie'];
Iterating an Array
Using for loop, forEach, map, filter, etc.
Method Chaining
javascript
let result = array.map().filter().reduce();
This
Refers to the current execution context.
Loops
For Loop
javascript
for (let i = 0; i < 5; i++) {
  // code to execute in each iteration
}
While Loop
javascript
let i = 0;
while (i < 5) {
  // code to execute in each iteration
  i++;
}
Do while Loop
javascript
let i = 0;
do {
  // code to execute in each iteration
  i++;
} while (i < 5);

SetTimeout and SetInterval
javascript
setTimeout(() => {
  // code to execute after a delay
}, 1000);

setInterval(() => {
  // code to execute repeatedly with a fixed time interval
}, 1000);

Day 6: Functions

DRY (Don't Repeat Yourself)
Encourages code reusability.

What are Functions?
Blocks of code designed to do one job.

Function Declarations and Definitions
javascript
function sayHello() {
  console.log('Hello!');
}

let add = function (a, b) {
  return a + b;
};

IIFE (Immediately Invoked Function Expression)
javascript
(function() {
  // code to execute immediately
})();
Function Parameters
javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}

greet('Alice');
Function Expressions
javascript
let multiply = function (a, b) {
  return a * b;
};

Arrow Function vs Normal Function
javascript
// Normal Function
function add(a, b) {
  return a + b;
}

// Arrow Function
let add = (a, b) => a + b;

Global Variable and Local Variable
Global variables are declared outside functions.
Local variables are declared inside functions.
This
Refers to the object that owns the function.

Day 7: Classes
Inheritance
Allows a class to inherit properties and methods from another class.
Exceptions
Handling errors and exceptions.
Sync, Asynchronous, Promises
Sync: Executes one task at a time.
Asynchronous: Allows multiple tasks to be executed concurrently.
Promises: Handles asynchronous operations and provides better control over callbacks.
Recursion
A function calling itself.


                                       Interview Questions:

Explain the difference between let, const, and var.
Answer: let and const are block-scoped, while var is function-scoped. const cannot be reassigned, but let can.

What are the primitive data types in JavaScript?
Answer: Number, Boolean, String, Null, Undefined, and Symbol.

Explain the difference between == and ===.
Answer: == performs type coercion, while === checks both value and type.

How do you handle asynchronous operations in JavaScript?
Answer: Using callbacks, Promises, or async/await.

What is the purpose of the this keyword in JavaScript?
Answer: this refers to the object that owns the function being executed.

How can you iterate over the elements of an array in JavaScript?
Answer: Using for loop, forEach, map, filter, etc.

Explain the concept of inheritance in JavaScript.
Answer: Inheritance allows a class to inherit properties and methods from another class, promoting code reuse.

What is a closure in JavaScript?
Answer: A closure is a function bundled with its lexical environment, allowing it to access variables from its outer scope even after the outer function has finished execution.

What is the difference between setTimeout and setInterval?
Answer: setTimeout executes the code once after a specified delay, while setInterval repeatedly executes the code with a fixed time interval.

Explain the purpose of Promises in JavaScript.
Answer: Promises are used to handle asynchronous operations and provide better control over callbacks, making code more readable and maintainable.