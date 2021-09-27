# In memory storage

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Understanding the JavaScript Call Stack

1. What is a ‘call’?
    - a call invokes a function within another function
2. How many ‘calls’ can happen at once?
    - 1
3. What does LIFO mean?
    - Last in, First Out Data structure
4. Draw an example of a call stack and the functions  that would need to be invoked to generate that call stack.
```
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}
```
5. What causes a Stack Overflow?
    - a stack overflow is caused when there is a recursive function without an exit point

## JavaScript error messages

1. What is a ‘refrence error’?
    - a reference error occurrs when a variable that has not been declared is used
2. What is a ‘syntax error’?
    - something that cannot be parsed in terms of syntax
3. What is a ‘range error’?
    - when an object is given an invalid length
4. What is a ‘type error’?
    - When data types are incompatible 
5. What is a breakpoint?
    - achieved by putting a debugger statement in your code in the line you want to break
6. What does the word ‘debugger’ do in your code?
    - stops the execution of the program to let developer examine the code

## Things I want to know more about

The debugger
>>>>>>> 09336e82c63594806a2c5be19c11753a119d0c34
