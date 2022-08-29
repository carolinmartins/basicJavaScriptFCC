## Iterate with JavaScript While Loops

`while` loop it runs while a specified condition is true and stops once that condition is no longer true.

### Exercise Instruction

Add the numbers 5 through 0 (inclusive) in descending order to `myArray` using a `while` loop.

### Solution
````
// Setup
const myArray = [];

// Only change code below this line
let a = 5;

while (a >= 0) {
  myArray.push(a);
  a--;
}

console.log(myArray);
````
