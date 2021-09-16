# React and Forms

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Forms

1. What is a ‘Controlled Component’?
  -  A controlled component is an input form element that renders a form while also controlling what happens on user input. 
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  - We should wait to store the users responses from the for into the state whent they submit.
  - We should wait because the state will be constantly updated as we type.
3. How do we target what the user is entering if we have an event handler on an input field?
  - `this.setState({value: event.target.value});`

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?
  - We could use ternary operators to shorten and simplify our code.
2. 

```
x === y = console.log(true) : console.log(false)
```