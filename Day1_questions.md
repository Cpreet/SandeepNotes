## General JavaScript

1- Who created JavaScript, and in what year was it developed?
 A-    JavaScript was created by Brendan Eich in 1995

2- What were the original and intermediate names of JavaScript before it got its current name?
A-     It was firstly called Mocha, later renamed LiveScript, and finally JavaScript.

3- Why is JavaScript considered a versatile programming language?
 A-    JavaScript supports cross-platform development, and we can use it for both server-side and client-side applications.

## Variables

1 What are the three ways to declare variables in JavaScript? Provide examples.
 A-    Let, Const & Var
    Let x = 10
    Const y = 20
    var z = 20
2 Compare var, let, and const. When would you use each?
A-     Var-Can be re declared. | not commonly used in modern javascript
    Let- Cannot be re declared but updated | Use for variables that will be reassigned
    Const- Cannot be re declared or updated | Encouraged for better readability and preventing accidental reassignments.
    
3 What does it mean when we say var is "function-scoped" and let and const are "block-scoped"?


4 Why is it recommended to avoid using var in modern JavaScript?
    - To avoid re-declaration
    
5 What are the rules for naming variables in JavaScript?
A-     1. Variables must start with a letter, `_`, or `$`.
    2. They can contain letters, digits, `_`, or `$` but cannot start with a digit.
    3. They are case-sensitive (e.g., `name` and `Name` are different).
    4. Reserved words (e.g., `let`, `function`) cannot be used as variable names.

6 What happens if you try to reassign a value to a variable declared with const?
A-     It shows error becouse a cont variable can be re declared


## Data Types

1 List the primitive data types in JavaScript and provide examples for each.
 A-    String - let Name= "Sandeep"
    Number - let Age = "27"
    Boolean - Let UseSocialmedia = "true"
    Undefined - let x,
    Null - let y = null,
    Symbol - : let y = Symbol('y'); 
    BigInt - let x=BigInt("123")

2 What is the difference between undefined and null in JavaScript?

A-     Null means that the value is defined as null (amswers)
    and undefined means the value is not defined as of now.

3 How does the Symbol data type differ from other primitive types? Provide an example.

4 What is BigInt, and why was it introduced in JavaScript?

5 Describe the non-primitive types in JavaScript. How do they differ from primitive types?
A-     Non-primitive data types in JavaScript are complex structures used to store multiple values or more advanced information.
    Primitive hold Single value --------- Non Primitive can hold multiple values
    Immutable-------------- Mutable


## Dynamic Typing

1 What does it mean that JavaScript is a "dynamically typed" language? Can you provide an example?
    
A-    JavaScript is a dynamically typed language, which means you don’t need to tell JavaScript what kind of data (like numbers, text, etc.)
    a variable will hold. The type of data can change while the program is running.
    
    Eg-
    let value = 10;      // value is a number
    value = "Hello";     // now value is a string
    value = true;        // now value is a boolean
