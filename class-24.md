<<<<<<< HEAD
# Mongo and Mongoose

[Main Page](https://jrdelmu.github.io/reading-notes/)

## nosql vs sql

### SQL

- predefined schema
- relational database
- vertically scalable
- table based databse
- not the best fit for hierarchical data storage

### noSQL

- dynamic schema for unstructured data
- non-relational database
- horizonally scalable
- document based
- good fit for hierarchical data storage

1. What kind of data is a good fit for an SQL database?
  -query instesive environment 
2. Give a real world example.
  - MySQL
3. What kind of data is a good fit a NoSQL database?
  - data that requires flexability or scaling
4. Give a real world example.
  - autotrader
5. Which type of database is best for hierarchical data storage?
  - NoSQL is best for hierarchical data storage
6. Which type of database is best for scalability?
  - SQL is best for vertical scaling while NoSQL is better for horizontal scaling.

1. What does SQL stand for?
  - Structured Query Language
2. What is a realational database?
  - a database based on relational algebra
3. What type of structure does a relational database work with?
  - tables
4. What is a ‘schema’?
  - schema is the way the data is organized
5. What is a NoSQL database?
  - a database that doesn't use the SQL structure
6. How does it work?
  - does not require schema
7. What is inside of a Mongo database?
  - data within the documents
8. Which is more flexible - SQL or MongoDB? and why.
  - MongoDB is more flexible because it allows for different formats of data
9. What is the disadvantage of a NoSQL database?
  - The duplicate data can be requim
=======
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
