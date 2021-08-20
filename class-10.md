# Error Handling & Debugging

[Main Page](https://jrdelmu.github.io/reading-notes/)

The **order of execution** is the order that statements are processed.  
  
Example:  
  
2.
```
function function sayHello() {
  return 'Hola' + userName();
};
```
3.
```
function userName(){
  let name = 'Jeff';
  return name;
};
```
1.
```
let hi =  sayHello();
```
4.
```
alert(hi);
```
The **debugger** keyword can be used to create a breakpoint in your code.  

Debugging options:
- Try a different browser because some issues can be browswer specific.
- console log numbers to see how far your code goes before stopping
- Strip down the code to the bare minimum
- Explaining the code could lead to a solution


