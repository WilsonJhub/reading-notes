# Reading

## React Docs - Thinking in React

  1. What is the *single responsibility* principle and how does it apply to components?
    - One such technique is the single responsibility principle, that is, a component should  
    ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
  2. What does it mean to build a ‘static’ version of your application?
    - To build a static version of your app that renders your data model,  
    you’ll want to build components that reuse other components and pass data using props.props  
    are a way of passing data from parent to child.
  3. Once you have a static application, what do you need to add?
    - create a render() method. 
  4. What are the three questions you can ask to determine if something is state?
    - Is it passed in from a parent via props? If so, it probably isn’t state.
    - Does it remain unchanged over time? If so, it probably isn’t state.
    - Can you compute it based on any other state or props in your component? If so, it isn’t state.
  5. How can you identify where state needs to live?
    - Identify every component that renders something based on that state. 
    - Find a common owner component (a single component above all the components that need the state in the hierarchy).
    - Either the common owner or another coponent higher up in te hierarchy should own the state. 
    - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## Higher-Order Functions

  1. What is a “higher-order function”?
    - Higher-order functions allow us to abstract over actions, not just values.
  2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
    - Line 2 is creating a method that says return 'm' if it is equal to or greater than value of 'n'
  3. Explain how either map or reduce operates, with regards to higher-order functions.
    - The map method transforms an array by applying a function to all of 
     its elements and building a new array from the returned values. The new array will have  
     the same length as the input array, but its content will have been mapped to a new form by the function.
  