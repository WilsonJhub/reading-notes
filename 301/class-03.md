# Reading 

 ## React Docs - lists and keys
    
  1. What does .map() return?
    - .map() will return a new UPDATED array with new values. 
  2. If i want to loop through an array and display each value in JSX, how do i do that in React?
    - You would need to use curly braces {}
  3. Each list item needs a unique ___.
    - key
  4. What is the purpose of a key?
    -  Keys help React identify which items have changed, are added, or are removed. 

 ## The Spread Operator
  1. What is the spread operator?
    - refers to the use of three dots (...) to expand an iterable object into the list of arguments. 
  2. List 4 things that the spread operator can do. 
    - expands an iterable object
    - “spreads” the array into separate arguments.
    - combine two arrays, an operation known as array concatenation
    - 
  3. Give an example of using the spread operator to combine two arrays.
    - const myArray = [`🤪`,`🐻`,`🎌`]
      const yourArray = [`🙂`,`🤗`,`🤩`]
      const ourArray = [...myArray,...yourArray]
  4. Give an example of using the spread operator to add a new item to an array.
    - const fewFruit = ['🍏','🍊','🍌']
      const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
  5. Give an example of using the spread operator to combine two objects into one.
    - const objectOne = {hello: "🤪"}
      const objectTwo = {world: "🐻"}
      const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}

 ## How to Pass Functions Between Components
  1. In the video, what is the first step that the developer does to pass functions between components?
    - creates a function wherever the state is that we're going to change. 
  2. In your own words, what does the increment function do?
    - first, we're creating a function that will .map() through the object 'people' and if (p), 
    which is referring to the properties within the object 'people' === 'name', then it will 
  3. How can you pass a method from a parent component into a child component?
    - import the specific compnonent into the child and use {this.props.___}
  4. How does the child component invoke a method that was passed to it from a parent component?
    - invoke the function using {}
