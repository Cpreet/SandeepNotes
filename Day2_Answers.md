### Arithmetic Operators
**Basic Arithmetic Operations**  
   1. "+" performs addition for numbers but concatenation for
      strings
      
      "-" always perform numeric subtraction and converts operands to number when needed
   
   2. The "++" operator is the increment operator. It      
      increases the value of a variable by 1.It can be used in two ways
         1. Post Increment(x++)
            ```
            let x = 5;
            let y = x++; // x's current value is assigned to y, then x is           incremented
            console.log(x); // 6
            console.log(y); // 5
            ```

         2. Pre Increment (++x)
            ``` javscript
            let x = 5;
            let y = ++x; // x is incremented first, then assigned to y
            console.log(x); // 6
            console.log(y); // 6
            ```

   3. - The % operator computes the remainder of the division
         of two numbers.

      - In 10 % 3, 10 is divided by 3, which gives a quotient of 3 and a remainder of 1.


**Advanced Arithmetic**  
   1. - The ** operator in JavaScript is the exponentiation    
         operator.
      - It raises the first operand (the base) to the power of the second operand (the exponent).


   2.    ```
         let x = 2;
         x **= 3; // x = x ** 3, which is 2 ** 3 = 8
         console.log(x); // 8
         ```


### Assignment Operators
3. **Simple Assignments**  
   - What does the `+=` operator do in JavaScript?  
   - How does the `-=` operator modify the value of a variable?  

4. **Complex Assignment**  
   - If `let x = 5; x *= 3;`, what will be the value of `x`?

### Comparison Operators
5. **Equality vs Strict Equality**  
   - What is the difference between `==` and `===` in JavaScript?  
   - Why does `0 == false` return `true` but `0 === false` return `false`?  

6. **Other Comparisons**  
   - What is the result of `"5" > 3` in JavaScript, and why?  
   - Explain the difference between `!=` and `!==`.

### Logical Operators
7. **Combining Conditions**  
   - What does the `&&` operator do? Provide an example.  
   - What is the role of `||` in JavaScript?  
   - How does the `!` operator invert Boolean values?  

### Ternary Operator
8. **Shorthand Conditional**  
   - Write a JavaScript expression using the ternary operator to check if a number is even or odd.  

### Conditionals
9. **If Statement**  
   - How does an `if` statement work in JavaScript?  
   - Provide an example where an `if` statement is used to validate user input.

10. **If...else Statement**  
    - When would you use an `if...else` statement?  
    - Rewrite the following code using an `if...else` statement:  
      ```javascript
      let isValid = true;
      console.log(isValid ? "Valid" : "Invalid");
      ```
