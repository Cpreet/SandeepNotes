### **LOOPS**

#### General Loop Questions
1. **Loop Fundamentals**  
   - A for loop runs a set number of times, while a while loop 
      runs as long as a condition is true. 
       
   - do...while loop is used when you want the code to run at least once before checking the condition.

2. **for Loop**  
   - ```JavaScript
      for (let i=0; i<=10; i++){
         if (i % 2 ===0){
         console.log(i)
         }
      }
      ```
   - In JavaScript, you can terminate a for loop prematurely using the break statement.

   ```JavaScript
      for (let i = 1; i <= 10; i++) {
       if (i === 5) {
        break; // Exits the loop when i equals 5
       }
       console.log(i);
        }
   ```

3. **while Loop**  
   - If the condition in a `while` loop is always `true`, it creates an **infinite loop**, running indefinitely unless interrupted by a `break` statement or external force.

   - ```JavaScript
         let i = 0;
         while (i < 3) {
         console.log(i);
         i++;
         }
      ```

4. **do...while Loop**  
   - A `while` loop checks the condition before running the    loop body, so it might not execute at all. A `do...while` loop checks the condition after running the loop body, so it always executes at least once.


   - ```JavaScript
      let input;
      do {clear
      input = prompt("Enter a word (type 'stop' to exit):");
      } while (input !== "stop");
      ```

5. **for...of Loop**  
   - What types of objects can a `for...of` loop iterate over?  
   - Write a `for...of` loop to iterate through the characters of a string.

6. **for...in Loop**  
   - What is the difference between a `for...of` loop and a `for...in` loop?  
   - Write a `for...in` loop to log the keys and values of the following object:  
     ```javascript
     const person = { name: "Alice", age: 25, city: "New York" };
     ```

7. **Edge Cases**  
   - What will happen if you declare `i` without `let` or `var` in a loop?  
   - Can you use `break` and `continue` in a `for...of` loop? Provide an example.

### **STRINGS**

#### String Basics
1. **String Creation**  
   - To create a string in JavaScript, you can use:
      1. Single quotes: `'your string'`
      2. Double quotes: `"your string"`
      3. Backticks: `` `your string` ``  

   -  -  **Single quotes** and **double quotes** are the same       for simple strings.
      - **Backticks** allow embedding variables and multi-line strings.

2. **String Immutability**  
   - Strings are **immutable** in JavaScript, meaning once created, they can't be changed. Any modification creates a new string instead of changing the original one.

   - Even though strings are immutable in JavaScript, you can still modify or manipulate them by creating new strings. You can use methods like replace(), slice(), or concat() to generate new strings based on the original one.
      
3. **String Length**  
   -  ```JavaScript
      const myString = "Hello, world!";
      const length = myString.length;
      console.log(length); // Output: 13
      ```
   - 5

4. **Indices and Accessing Characters**  
   - Indices Strings
      ```javascript
      str[O], str[1], str[2]
      ```  
   - Undefined

#### Template Literals and Interpolation
5. **Template Literals**  
   - Template literals are strings enclosed in backticks (`) instead of quotes (' or "). They are more flexible than regular strings. Here's how they differ:
      1. Interpolation:
         You can embed variables and expressions directly using ${}.
      2. Multi-line Strings
         Template literals support multi-line text without special characters.
      3. Expressions
         Any JavaScript code can be used inside ${}.

   Regular strings don't have these features and need concatenation (+) or escape characters (\n) for similar results.
   -  ```js 
      `Hello, my name is ${name}.`
      ```

6. **String Interpolation**  
   - String interpolation in JavaScript is a way to include variables or expressions directly inside a string. It uses template literals, which are strings enclosed in backticks (`).
    
   - ```javascript
      const num1 = 10;
      const num2 = 20;
      const sum = `The sum of ${num1} and ${num2} is ${num1 + num2}.`;
      console.log(sum);
      // Output: The sum of 10 and 20 is 30.
      ```

#### String Methods
7. **Common String Methods**  
   - What does the `str.trim()` method do?  
   - Write code to convert `"   Hello World   "` to `"hello world"` using string methods.  
   - How does the `str.slice(start, end?)` method work? Provide an example.

8. **String Operations**  
   - How can you combine two strings in JavaScript?  
   - Write code to replace the word `"bad"` with `"good"` in the string `"This is a bad day."`

9. **Character Operations**  
   - What is the difference between `str.charAt(idx)` and `str[idx]`?  
   - Write code to find the character at the 3rd position in the string `"JavaScript"`.

