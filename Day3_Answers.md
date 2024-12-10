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
   - How can you terminate a `for` loop prematurely? Provide an example.

3. **while Loop**  
   - What happens if the condition in a `while` loop is always `true`?  
   - Rewrite this `for` loop using a `while` loop:  
     ```javascript
     for (let i = 0; i < 3; i++) {
         console.log(i);
     }
     ```

4. **do...while Loop**  
   - How is a `do...while` loop different from a `while` loop?  
   - Write a `do...while` loop that prompts a user until they enter the word "stop."

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

