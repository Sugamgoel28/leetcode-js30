<h1 align="center">Leetcode: 30 Days of Javascript🎯</h1>

<h5 align="center"><i> Hi Stranger! I accept the thirty days javascript challenge by LeetCode, this log will show my progress, Wish me Consistency!✨</i></h5>
<h6 align="center"><i>Let not be strangers any more? 👉<a href= "https://www.linkedin.com/in/sugam-goel-india/">Connect</a></i></h6> 
<hr>

<h3> <u>Day 1: Create Hello World Function </u></h3>

Question 1: Write a function create HelloWorld. It should return a new function that always returns "Hello World".</br>

Solution:
 <pre>
  <code>
      var createHelloWorld = function() {
          return function(...args) {
              return "Hello World";
          }
      };
    </code>
</pre>
<hr>
<h3> <u>Day 2: Counter </u></h3>

Question 2: Given an integer n, return a counter function. This counter function initially returns n and then returns 1 more than the previous value every subsequent time it is called (n, n + 1, n + 2, etc).

Solution:
 <pre>
  <code>
     var createCounter = function(n) {
       return function() {
           return n++
        };
    };
    </code>
</pre>
<hr>






<hr>




