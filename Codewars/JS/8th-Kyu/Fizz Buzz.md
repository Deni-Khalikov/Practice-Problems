# Fizz Buzz 

### 1st solve 29 Nov 2021 
---
```js
// Return an array
function fizzbuzz(n)
{
  var array = [];
  
  // if condition is true it stops there
  
  for(let i = 1; i <= n; i++) {
      if (i % 3 === 0 && i % 5 === 0) {
        array.push("FizzBuzz");
      } else if (i % 5 === 0) {
        array.push("Buzz");
      } else if (i % 3 === 0) {
        array.push("Fizz");
      } else {
        array.push(i);
      }   
    }
  return array;

}
```
---
Thoughs: damn this one was much harder than the other ones.

link https://www.codewars.com/kata/5300901726d12b80e8000498/train/javascript
