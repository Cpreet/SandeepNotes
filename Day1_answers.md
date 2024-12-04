## General JavaScript

1. JavaScript was created by Brendan Eich in 1995

2. It was firstly called Mocha, later renamed LiveScript, and finally JavaScript.

3. JavaScript supports cross-platform development, and we can use it for both server-side and client-side applications.

## Variables

1. 
    let, const & var
    ```javascript
    let x = 10
    const y = 20
    var z = 20
    ```

    - `var`: Can be re declared. | not commonly used in modern javascript
   
    - `let`: Cannot be re declared but updated | Use for variables that will be reassigned

    - `const`: Cannot be re declared or updated | Encouraged for better readability and preventing accidental reassignments.
    
2.   
    - var is function-scoped: If you declare a variable with var, it works for the whole function. It does not care about {}

    - let and const are blocked-scoped : the work only inside the {} block where they are declared. To avoid re-declaration
    
3. 
    1. Variables must start with a letter, `_`, or `$`.
    
    2. They can contain letters, digits, `_`, or `$` but cannot start with a digit.
    
    3. They are case-sensitive (e.g., `name` and `Name` are different).
    
    4. Reserved words (e.g., `let`, `function`) cannot be used as variable names.
                    
    It shows error becouse a const variable cannot be re-declared


## Data Types

 A-    String - let Name= "Sandeep"
    Number - let Age = "27"
    Boolean - Let UseSocialmedia = "true"
    Undefined - let x,
    Null - let y = null,
    Symbol - : let y = Symbol('y'); 
    BigInt - let x=BigInt("123")


A-     Null means that the value is defined as null (amswers)
    and undefined means the value is not defined as of now.

a-  A symbol is special type of primitive in JS that is always unique, even if it has the same description.
    Not converted to string like other primitives types

a-      

A-     Non-primitive data types in JavaScript are complex structures used to store multiple values or more advanced information.
    Primitive hold Single value --------- Non Primitive can hold multiple values
    Immutable-------------- Mutable


## Dynamic Typing

    
A-    JavaScript is a dynamically typed language, which means you don’t need to tell JavaScript what kind of data (like numbers, text, etc.)
    a variable will hold. The type of data can change while the program is running.
    
    Eg-
    let value = 10;      // value is a number
    value = "Hello";     // now value is a string
    value = true;        // now value is a boolean
