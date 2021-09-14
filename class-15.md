# State and Props

[Main Page](https://jrdelmu.github.io/reading-notes/)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  - Based off the diagram, the 'render' happens first.
2. What is the very first thing to happen in the lifecycle of React?
  - The very first thing to happen during the lifecycle of React is the mounting phase. During this phase `constructor`, `static getDerivedStateFromProps`, `render`, `componentDidMount`, and `UNSAFE_componentWillMount` all occur.
3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`
 - `constructor`
 - `render`
 - `React Updates`
 - `componentDidMount`
 - `componentWillUnmount`
4. What does componentDidMount do?
 - allows for the execution of React code when a component is placed in DOM. 


1. What types of things can you pass in the props?
  - You pass in what you want to initialize your component to or what you want your component to render like. 
  - exmaples:
    - titles
    - text
    - images
2. What is the big difference between props and state?
 - The difference between props and state is that in props you pass into a component from the outside while in state everything is handled internally. 
 - changing state inside of an application will re-render that part of the application
3. When do we re-render our application?
 - You would re-render an application when you need to update it based on an event caused by the user.
4. What are some examples of things that we could store in state?
 - Updated values from forms can be stored into state.

 ## Things I want to know more about
 - When is it best to use state vs props?