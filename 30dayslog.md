<h1 align="center">Leetcode: 30 Days of Javascript🎯</h1>

<h5 align="center"><i> Hi Stranger! I accept the thirty days javascript challenge by LeetCode, this log will show my progress, Wish me Consistency!✨</i></h5>
<h6 align="center"><i>Let not be strangers any more? 👉<a href= "https://www.linkedin.com/in/sugam-goel-india/">Connect</a></i></h6> 
<hr>

<h3> <u>Day 1: Create Hello World Function </u></h3>

Question 1: Write a function create HelloWorld. It should return a new function that always returns "Hello World".</br>

Solution:
```cpp
      var createHelloWorld = function() {
          return function(...args) {
              return "Hello World";
          }
      };
```    
<hr>
<h3> <u>Day 2: Counter </u></h3>

Question 2: Given an integer n, return a counter function. This counter function initially returns n and then returns 1 more than the previous value every subsequent time it is called (n, n + 1, n + 2, etc).

Solution:
```cpp
     var createCounter = function(n) {
       return function() {
           return n++
        };
    };
```
<hr>
<h3> <u>Day 3: To be or Not to Be </u></h3>

Question 2: Write a function expect that helps developers test their code. It should take in any value val and return an object with the following two functions.

<kbd>toBe(val)</kbd> accepts another value and returns true if the two values === each other. If they are not equal, it should throw an error "Not Equal".
<kbd>notToBe(val)</kbd> accepts another value and returns true if the two values !== each other. If they are equal, it should throw an error "Equal".

Solution:
```cpp
    var expect = function(val) {
    function toBe(val2){
        if(val === val2){
             return true
             }
        else{
            throw new Error('Not Equal')
        }
    }
    function notToBe(val2){
        if(val !== val2) {
            return true
            }
        else{
            throw new Error ("Equal")
        }
    }
    return {
        toBe, notToBe
    }
};
```
<hr>
<h3> <u>Day 4: Counter 2 </u></h3>

Question: Write a function createCounter. It should accept an initial integer init. It should return an object with three functions.

The three functions are:

<kbd>increment()</kbd> increases the current value by 1 and then returns it.<br>
<kbd>decrement()</kbd> reduces the current value by 1 and then returns it.<br>
<kbd>reset()</kbd> sets the current value to <kbd>init</kbd> and then returns it.<br>

Solution:
```cpp
    var createCounter = function(init) {
    let presentCount = init;

    return{
        increment: ()=> ++presentCount,
        decrement: ()=> --presentCount,
        reset: ()=> presentCount = init 
    }
};
```
<hr>



