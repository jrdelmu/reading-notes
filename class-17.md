# Passing Functions as Props

[Main Page](https://jrdelmu.github.io/reading-notes/)

## lists and keys

1. What does `.map()` return?
  - `.map()` will create an array utlilizing a parent array. This method is none mutating.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
  - The values would be place in `ReactDOM.render()`.
3. Each list item needs a unique ____.
  - Each list item needs a unique **key**.
4. What is the purpose of a key?
  - The purpose of a key is to assist React in identifying which items have changed, are added, or are removed.

## The Spread Operator

1. What is the spread operator?
  - Allows an iterable such as an array to be expanded in places where arguments or elements are expected.
2. List 4 things that the spread operator can do.
  - Copying an array
  - Concatenating or combining arrays
  - Using math functions
  - Using an array as arguments 
3. Give an example of using the spread operator to combine two arrays.
  - Example:
  ```
  const partOne = [1,2,3]
  const partTwo = [4,5,6]
  const partThree = [...partOne, ...partTwo]
  result: [1,2,3,4,5,6]
  ```
4. Give an example of using the spread operator to add a new item to an array.
  - Example:
  ```
  const orgArr = ['cat']
  let newArr;

  newArr = [...orgArr, 'dog']
  ```
5. Give an example of using the spread operator to combine two objects into one.
  - Example:
  ```
  let make = {
    make: 'acura'
  }

  let model = {
    model: 'integra'
  }

  let car = {
    ...make,
    ...model
  }

  result:
  {
       make: 'acura',
      model: 'integra'
  }
  ```
## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
  - The first step is to create the function wherever state is that is going to be changed.
2. In your own words, what does the increment function do?
  - Everytime the `p.name` is strictly equal to `name` the count that is incremented by 1.
3. How can you pass a method from a parent component into a child component?
  - You can pass a method from a parent component into a child component by referencing the function. In the video the increment function was reference in the child component with `increment = {this.increment}`
4. How does the child component invoke a method that was passed to it from a parent component?
  - In the video the method is invoked using `this.props.increment()`

## Things I want to know more about

what are the advantages to using Bootstrap over Flexbox?
