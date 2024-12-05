### Arithmetic Operators
**Basic Arithmetic Operations**  
   1. "+" performs addition for numbers but concatenation for
      strings
      
      "-" always perform numeric subtraction and converts operands to number when needed
   
   2. The "++" operator is the increment operator. It      
      increases the value of a variable by 1.It can be used in two ways
         1. Post Increment(x++)
            ```js
            let x = 5;
            let y = x++; // x's current value is assigned to y, then x is           incremented
            console.log(x); // 6
            console.log(y); // 5
            ```

         2. Pre Increment (++x)
            ``` javascript
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


   2.    ```js
            let x = 2;
         x **= 3; // x = x ** 3, which is 2 ** 3 = 8
         console.log(x); // 8
         ```


### Assignment Operators
**Simple Assignments**  
   - The += operator adds the value on the right to the variable on the left and updates the variable.
      ```JavaScript
      let x = 5;
      x += 3; // x is now 8
      ```
  
   - The -= operator subtracts the value on the right from the variable on the left and updates the variable with the result.  
      ```JavaScript
      let x = 10;
      x -= 3; // x is now 7
      ```

**Complex Assignment**  
   -  ```JavaScript
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
   **Combining Conditions**  
   - The && operator means AND. It checks if both conditions   
      are true. 
      ```JavaScript
         let x = 5;
         let y = 10;
         if (x > 0 && y > 0) {
        console.log("Both numbers are positive.");
         }
      ```
   - The || operator is the logical OR operator in JavaScript. It checks if at least one condition is true. If any condition is true, it returns true; otherwise, it returns false.
   ``` js
         let x = 5;
         let y = -10;
         if (x > 0 || y > 0) {
         console.log("At least one number is positive.");
         }
   ```
   -  The ! operator is the logical NOT operator in     
      JavaScript. It inverts a Boolean value:
      - If the value is true, it becomes false.
      - If the value is false, it becomes true.  

### Ternary Operator
**Shorthand Conditional**  
   
   - ```js
      let number = 7;
      let result = (number % 2 === 0) ? "Even" : "Odd";
      console.log(result); // Output: "Odd"
      ```

### Conditionals
**If Statement**  
   - An if statement in JavaScript executes a block of code only if the condition is true. If the condition is false, the code block is skipped.
   For Ex.
      ```js
      let age = 18;
      if (age >= 18) {
      console.log("You are an adult.");
      }
      ```

   - ```JavaScript
      let username = prompt("Enter your username:");
      if (username) {
      console.log("Welcome, " + username + "!");
      } else {
      console.log("Username cannot be empty.");
      }
      ```


**If...else Statement**    
   -  You use an if...else statement when you want to execute  
      one block of code if a condition is true and a different 
      block of code if the condition is false. 

   -  ```js
      let isvalid = true;
      
      if (isValid){
         console.log("Valid");
      } else{
         console.log("Invalid")
      }
      ```
