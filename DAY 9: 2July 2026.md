Day 9 – JavaScript Variables and Data Types

Date: 2 July 2026
Topic: JavaScript Variables and Data Types
Training: MERN Stack Development

1. Introduction

Today, I learned about JavaScript variables and data types.

JavaScript is a programming language used to make websites interactive and dynamic. Variables are used to store information, while data types define the kind of information stored in a variable.

2. What are Variables?

A variable is a container used to store data values.

In JavaScript, we can declare variables using three keywords:

1. "var"
2. "let"
3. "const"

Example:

var name = "Muskan";
let age = 20;
const city = "Ludhiana";

console.log(name);
console.log(age);
console.log(city);

Output:

Muskan
20
Ludhiana

3. Difference Between var, let and const

Keyword| Description
var| Can be redeclared and updated.
let| Can be updated but cannot be redeclared in the same scope.
const| Cannot be reassigned after declaration.

Example:

var a = 10;
a = 20;

let b = 30;
b = 40;

const c = 50;

console.log(a);
console.log(b);
console.log(c);

Output:

20
40
50

4. What are Data Types?

Data types define the type of value stored in a variable.

JavaScript has several data types.

A. String

A string is used to store text.

let name = "Muskan";
console.log(name);

B. Number

A number is used to store numeric values.

let age = 20;
let price = 99.5;

console.log(age);
console.log(price);

C. Boolean

A Boolean represents either true or false.

let isStudent = true;
console.log(isStudent);

D. Undefined

A variable that has been declared but not assigned a value is undefined.

let marks;
console.log(marks);

E. Null

Null represents an intentional absence of a value.

let result = null;
console.log(result);

F. Object

An object stores data in key-value pairs.

let student = {
    name: "Muskan",
    age: 20,
    course: "BTech"
};

console.log(student);

G. Array

An array stores multiple values in a single variable.

let subjects = ["HTML", "CSS", "JavaScript"];

console.log(subjects);

5. Checking Data Types Using typeof

JavaScript provides the "typeof" operator to check the data type of a value.

Example:

let name = "Muskan";
let age = 20;
let isStudent = true;

console.log(typeof name);
console.log(typeof age);
console.log(typeof isStudent);

Output:

string
number
boolean

6. Rules for Naming Variables

Some important rules for naming JavaScript variables are:

- Variable names can contain letters, numbers, underscores, and dollar signs.
- A variable name cannot start with a number.
- Spaces are not allowed in variable names.
- JavaScript keywords cannot be used as variable names.
- Variable names are case-sensitive.
- Use meaningful names to make code easy to understand.

Example:

let studentName = "Muskan";
let totalMarks = 450;

7. Practical Program

JavaScript Code:

let studentName = "Muskan";
let age = 20;
let course = "BTech";
let isPassed = true;

console.log("Student Name:", studentName);
console.log("Age:", age);
console.log("Course:", course);
console.log("Passed:", isPassed);

Output:

Student Name: Muskan
Age: 20
Course: BTech
Passed: true

8. Learning Outcomes

Today, I learned:

- The basics of JavaScript.
- How to declare variables using var, let, and const.
- The difference between var, let, and const.
- Different JavaScript data types.
- How to use the typeof operator.
- Rules for naming variables.
- How to store and display data using console.log().

9. Practical Task

Create a JavaScript program that stores the following information:

- Student name
- Roll number
- Age
- Course name
- Marks
- Pass/fail status

Display all the information using "console.log()".

10. Conclusion

Today, I learned about JavaScript variables and data types. I practiced declaring variables, storing different types of values, and displaying them using console.log(). These concepts are important for understanding JavaScript programming.
