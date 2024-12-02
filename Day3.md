# LOOPS & STRINGS
Loops in JavaScript are used to execute a block of code repeatedly, as long as a specified condition is true.
Here are the common types of loops in JavaScript:
## LOOPS

1. for Loop
Executes a block of code a specific number of times.

```javascript
for (let i = 0; i < 5; i++) {
    console.log(i); // 0, 1, 2, 3, 4
}
```

2. while Loop
Repeats as long as a specified condition is true.

```javascript
let i = 0;
while (i < 5) {
    console.log(i); // 0, 1, 2, 3, 4
    i++;
}
```

3. do...while Loop
Executes the block of code at least once, then continues while the condition is true.

```javascript
let i = 0;
do {
    console.log(i); // 0, 1, 2, 3, 4
    i++;
} while (i < 5);
```
4. for...of Loop
Iterates over iterable objects (like arrays, strings, etc.).

```javascript
const arr = [10, 20, 30];
for (let value of arr) {
    console.log(value); // 10, 20, 30
}
```

5. for...in Loop
Iterates over the properties of an object.

```javascript
const obj = {a: 1, b: 2, c: 3};
for (let key in obj) {
    console.log(key, obj[key]); // a 1, b 2, c 3
}
```

## STRINGS
Strings in JavaScript are sequences of characters used to store and manipulate text. They are enclosed in

single quotes ('), double quotes ("), or backticks (\`\`). 
Here’s a quick guide

1. Create Strings

```javascript
let str = “Apna College”
```
2. String Length

```javscript
let str = "Some string"
str.length
```
3. Indices Strings

```javascript
str[O], str[1], str[2]
```

### Template Literals in JS
A way to have embedded expressions in strings

`this is a template literal`

### String Interpolation
To create strings by doing substitution of placeholders

`string text ${expression} string text`

### String Methods in JS
These are built-in functions to manipulate a string


```javascript
str.toUpperCase( )
str.toLowerCase( )
str.trim( ) // removes whitespaces
str.slice(start, end?) // returns part of string
str1.concat( str2 ) // joins str2 with str1
str.replace( searchVal, newVal )
str.charAt( idx )
```
- Strings are immutable, meaning they cannot be changed after being created,but you can create new
- strings based on operations
