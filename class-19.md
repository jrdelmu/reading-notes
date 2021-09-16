# Putting it all together

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Thinking in React

1. What is the single responsibility principle and how does it apply to components?
  - The single repsonsibility principle applies to components that grow to a certain size. Once it reaches that size it should be broken down into smaller subcomponents. 
2. What does it mean to build a ‘static’ version of your application?
  - A static version of an application is a rendered version of the UI without the interactivity or logic.
3. Once you have a static application, what do you need to add?
  - Once the static application is built you can start to apply state for interactivity.
4. What are the three questions you can ask to determine if something is state?
  - If it is passed in from a parent by props then it is NOT state.
  - if it reamins unchanged overtime then it is NOT state.
  - If you can compute it based on any other state or props in your component then it is NOT state.
5. How can you identify where state needs to live?
  - Identify all components that render something based on state
  - find a common component owner
  - A common owner or a component higher up in the hierachy should own the state
  - Create a new component solely for holding the state and place it somewhere above the common owner component if you can't find a component where it makes sense to own the state.

## Higher-Order Functions

1. What is a “higher-order function”?
  - functions that work with other functions and can accept other functions as arguments and return a function
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
  - line two is returning a function
3. Explain how either map or reduce operates, with regards to higher-order functions.
  - the map method itself is a higher-order function because it returns a function when executed. 

## Things I want to know more about

I would like to go more in depth with both map and reduce.