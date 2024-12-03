### **General Questions**
1. **Array Basics**  
   - How do you create an array in JavaScript? Provide an example.  
   - What are array indices, and how are they used to access elements?  

### **Array Methods**

#### **Push Method**
2. **Adding Elements**  
   - What does the `push()` method do in JavaScript?  
   - Given the array `let numbers = [1, 2, 3];`, what will be the output of the following code?  
     ```javascript
     numbers.push(4, 5);
     console.log(numbers);
     ```  
#### **Pop Method**
3. **Removing Elements from End**  
   - What is the purpose of the `pop()` method?  
   - Write a JavaScript function that removes and returns the last element of an array. If the array is empty, log "Underflow."  

#### **toString Method**
4. **Converting Arrays to Strings**  
   - How does the `toString()` method work for arrays?  
   - What will be the output of the following code?  
     ```javascript
     let arr = ["apple", "banana", "cherry"];
     console.log(arr.toString());
     ```
#### **Concat Method**
5. **Joining Arrays**  
   - Explain the `concat()` method in JavaScript.  
   - Write code to merge the following arrays into a single array:  
     ```javascript
     let arr1 = [1, 2];
     let arr2 = [3, 4];
     let arr3 = [5, 6];
     ```

#### **Unshift Method**
6. **Adding Elements to Start**  
   - What does the `unshift()` method do?  
   - What will the array look like after the following code executes?  
     ```javascript
     let arr = [30, 40];
     arr.unshift(10, 20);
     console.log(arr);
     ```

#### **Shift Method**
7. **Removing Elements from Start**  
   - How does the `shift()` method work?  
   - Write a function to remove and return the first element of an array. If the array is empty, return `"Underflow."`

### **Scenario-Based Questions**
8. **Practical Scenarios**  
   - How would you add an element to the start and end of an array in one operation?  
   - Write code to remove the last element of an array, add a new element to the beginning, and then convert the array to a string.  

9. **Combination of Methods**  
   - Using the following array, demonstrate the use of `push()`, `pop()`, `unshift()`, and `shift()` in sequence.  
     ```javascript
     let arr = [100, 200, 300];
     ```
10. **Custom Implementation**  
    - Write a function to implement a stack using an array. Ensure that the function has methods for `push`, `pop`, and checking if the stack is empty.  

### **Edge Cases**
11. **Behavior Questions**  
    - What happens when you call `pop()` or `shift()` on an empty array?  
    - Can the `toString()` method modify the original array? Why or why not?

12. **Multiple Arrays**  
    - What will be the output of the following code?  
      ```javascript
      let a = [1];
      let b = [2, 3];
      let c = [4];
      let result = a.concat(b, c);
      console.log(result);
      ```
