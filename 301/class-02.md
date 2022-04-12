# State and Props

## React Lifecycle

1. **Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**
    - render will come before 'componentDidMount'  
2. **What is the very first thing to happen in the lifecycle of React?**
    - Mounting is the very first thing to occur in the lifecycle of React. Below is the flow of the Mounting phase:  
    Mounting Phase:
        - Constructor, static, getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount.  
3. **Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**
    - 
4. **What does componentDidMount do?**
    - This is a method that is invoked immediately after acomponent is mounted. If something is being loaded to a network request or being initiailized by the DOM then it needs to go in the componentDidMount().