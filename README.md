# Technical Test

1. Given a string, reverse each word in the sentence**
  `"Welcome to this Javascript Guide!"` should be become `"emocleW ot siht tpircsavaJ !ediuG"`

2. Write a function that finds the longest word in a sentence.
```
console.log(findLongestWord('The quick brown fox jumps over the lazy dog'));
// Output: 'quick'
```

3. Create function so the following code would work?
```
var arr = [1, 2, 3, 4, 5];
var avg = average(arr);
console.log(avg);  // => 3
```

4. Design a Calculator interface for 2 number inputs which can perform sum, difference, product and dividend whenever invoked on the same interface
```
// Example
const calc12And5 = Calculator(12, 5);
calc12And5.sum(); // 17
calc12And5.difference(); // 7
calc12And5.product(); // 60
calc12And5.dividend(); // 2
```

5. Create function to execute the given list of asynchronous functions in parallel and return the results as an array to the callback
```
function asyncFunc1(callback) {
  setTimeout(() => {
    callback(1);
  }, 3000);
}
 
function asyncFunc2(callback) {
  setTimeout(() => {
    callback(2);
  }, 2000);
}
 
function asyncFunc3(callback) {
  setTimeout(() => {
    callback(3);
  }, 1000);
}
```

6. Write a function that returns the Fibonacci sequence up to a given number of terms. 
```
// Example
generateFibonacci(9) // will return [0, 1, 1, 2, 3, 5, 8, 13, 21]
```