# Create Hello World Function
**LeetCode Path:** [30 Days of JavaScript Challenge](https://leetcode.com/studyplan/30-days-of-javascript/)<br>
**Language:** JavaScript  
**Topic:** Basics / Functions 

## Problem
Write a function createHelloWorld. It should return a new function that always returns "Hello World".<br>
[Create JavaScript Function](https://leetcode.com/problems/create-hello-world-function/description/?envType=study-plan-v2&envId=30-days-of-javascript)


## Solution 
```var createHelloWorld = function() {```
- Declares a variable called createHelloWorld and assigns a function to it.
  
createHelloWorld Function
- creates a child function using ```return(...args)```.

child Function
- ```...args``` accepts an infinite number of arguments.
- ```return("Hello World")``` makes the string "Hello World" a value that can be assigned to a variable or passed as an argument to another function.

console.log() vs return() 
- ```console.log()``` outputs the string to the console. ```return()``` converts the string as a value that can be used in the code for storing a variable or passing the value to another function.



```javascript
var createHelloWorld = function() {
    
    return function(...args) {
        return("Hello World")
    }
}
```
