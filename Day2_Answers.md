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
**Simple Assignments**  
   - The += operator adds the value on the right to the variable on the left and updates the variable.
      ```
      let x = 5;
      x += 3; // x is now 8
      ```
  
   - The -= operator subtracts the value on the right from the variable on the left and updates the variable with the result.  
      ```
      let x = 10;
      x -= 3; // x is now 7
      ```

**Complex Assignment**  
   -  ```
      let x = 5;
      x *= 3; // x = 5 * 3 = 15
      ```

### Comparison Operators
**Equality vs Strict Equality**  
   - == checks for value equality with type coercion.
   
      === checks for both value and type equality (strict comparison).  

   - The difference between 0 == false and 0 === false comes down to type coercion:
     - false is automatically coerced into the number 0 (since false is considered 0 when converted to a number).
     - 0 is a number and false is a boolean, so since they are of different types, the comparison is false.

  
6. **Other Comparisons**  
   - JavaScript performs type coercion when comparing values with different types.
      - JavaScript converts the string "5" to a number for the comparison and 5 is greater than 3 the value will be true.
   
   - The difference between != and !== in JavaScript is similar to the difference between == and ===:
      -  != allows type coercion, so it compares values after converting them to the same type.
      -  !== checks both the value and the type, without type coercion. 

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
