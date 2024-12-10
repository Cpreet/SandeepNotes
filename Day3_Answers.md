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


   -  ```JavaScript
      let input;
      do {
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
   - How can you create a string in JavaScript?  
   - What are the differences between single quotes, double quotes, and backticks?

2. **String Immutability**  
   - What does it mean that strings are immutable in JavaScript?  
   - If strings are immutable, how can you modify or manipulate them?

3. **String Length**  
   - How do you find the length of a string in JavaScript?  
   - What will `console.log("Hello".length);` output?

4. **Indices and Accessing Characters**  
   - How can you access individual characters in a string?  
   - What happens if you try to access an index that is out of bounds in a string?

#### Template Literals and Interpolation
5. **Template Literals**  
   - What are template literals, and how are they different from regular strings?  
   - Write a template literal to include a variable `name` in the sentence:  
     `"Hello, my name is <name>."`

6. **String Interpolation**  
   - Explain how string interpolation works in JavaScript.  
   - Write an example of string interpolation to calculate the sum of two variables.

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

