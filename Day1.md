## Javascript
JavaScript is a lightweight, versatile programming language used for web development. JavaScript was
created by Brendan Eich in 1995 while working at Netscape. It was originally developed in just 10 days
and was initially called Mocha, later renamed LiveScript, and finally JavaScript.

## Variable
In JavaScript, variables are used to store data values. You can declare variables using var, let, or const.

### Syntax:
```javascript
let name = "John"; // Changeable variable
const age = 30; // Constant, cannot be reassigned
var city = "New York"; // Old way, less commonly used
```
### Key Points:

- let: Block-scoped, can be reassigned.
- const: Block-scoped, cannot be reassigned.
- var: Function-scoped, avoid in modern code.

### Here are the rules for JavaScript variables:

1. Variables must start with a letter, `_`, or `$`.
2. They can contain letters, digits, `_`, or `$` but cannot start with a digit.
3. They are case-sensitive (e.g., `name` and `Name` are different).
4. Reserved words (e.g., `let`, `function`) cannot be used as variable names.
5. Use descriptive names for clarity.

## JavaScript has the following data types:

1. Primitive Types

- String: Text values.
Example: let name = "John";
    
Number: Numeric values (integers or decimals).
Example: let age = 25;

Boolean: True or false.
Example: let isActive = true;

Undefined: A variable declared but not assigned a value.
Example: let x;

Null: Represents an empty or non-existent value.
Example: let y = null;

Symbol: Unique identifiers (introduced in ES6).
Example: let id = Symbol('id');

BigInt: For very large integers (introduced in ES11).
Example: let bigNum = 123n;

2. Non-Primitive Types (Objects)

Object: Collections of key-value pairs.
Example: let person = { name: "John", age: 30 };

Array: Ordered list of values.
Example: let colors = ["red", "blue"];

Function: A block of code that can be executed.
Example: function greet() { return "Hello"; }

JavaScript variables are dynamically typed, meaning their type can change.
