# ARRAYS

Collections of items

## Create Array

```javascript
let heroes = [ “ironman” , “hulk” , “thor” , “batman” ]
```

## Array Indices

- arr[0], arr[1], arr[2] ....

## Array Methods
- Push(): add to end

Explanation:
- `push(value)` adds `value` to the end of the array.
- The array acts as a stack, where elements are added to the top.

Eg:
```javascript
let array = [1, 2, 3];
array.push(4);
console.log(array); // Output: [1, 2, 3, 4]
```
- Pop( ) : delete from end & return

Explanation:
- `pop()` removes the last element of the array (top of the stack).
- Returns the removed element.
- If the stack is empty, it prevents underflow.

```javascript
let stack = [10, 20, 30];
// Pop operation
function pop() {
    if (stack.length === 0) {
        console.log("Stack Underflow");
        return null;
    } else {
        let removed = stack.pop();
        console.log(removed + " popped from stack");
        return removed;
    }
}
```
Eg:
```javascript
pop(); // Output: 30 popped from stack
pop(); // Output: 20 popped from stack
console.log("Stack:", stack); // Output: Stack: [10]
```
- ToString(): converts array to string

Explanation:
- The toString() method converts all elements of an array into a single string, separated by
commas.
- It does not modify the original array.

```javascript
let array = [10, 20, 30, 40];
// Convert array to string
let result = array.toString();
console.log(result); // Output: "10,20,30,40"
```
- Concat(): joins multiple arrays & returns result

```javascript
let array1 = [10, 20, 30];
let array2 = [40, 50];
let array3 = [60, 70];
// Concatenate arrays
let result = array1.concat(array2, array3);
console.log(result); // Output: [10, 20, 30, 40, 50, 60, 70]
```

Explanation:
- concat() joins two or more arrays and returns a new array.
- It does not modify the original arrays.
- You can pass multiple arrays or individual values as arguments.

- Unshift(): add to start
```javascript
let array = [20, 30, 40];
// Add elements to the start
array.unshift(10);
console.log(array); // Output: [10, 20, 30, 40]
```

Explanation:
- unshift(value1, value2, ...) adds one or more elements to the beginning of the array.
- Returns the new length of the array.

- Shift(): delete from start & return

```javascript
let array = [10, 20, 30, 40];
// Remove the first element
let removed = array.shift();
console.log(removed); // Output: 10 (removed element)
console.log(array); // Output: [20, 30, 40]
```

Explanation:
- shift() removes the first element from an array.
- Returns the removed element.
- The array is modified, and its length decreases by one.
