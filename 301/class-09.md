# Functional Programming

1. What is functional programming?  
  - Functional programming is a prgramming paradigm- a style of buldiing the structure of computer programs  
  that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.
2. What is a pure function and how do we know if something is a pure function?  
  - It returns the same result if given the ame arguments.  
  - It does not cause any observable side effects.
3. What are the benefits of a pure function?
  - 
4. What is immutability?
  - When data is rendered as *immutable*, its state cannot change after it 's created.  
  - If we are wanting to change the state of data, then we need to create an entirely different object. 
5. What is Referential transparency?
  - If a function consistently yeilds the same result for the same input, it is considered referentially transparent.  



## Node JS Tutorial for beginners #6 - Modules and require()  

1. What is a module?  
  - A logical module contains certain functionalities specific to its reason of design. These functionalities can be called upon within our main module whenever we are needing to use them. For example: One module can hold a function that counts things. We then can call upon that module when needed. 
2. What does the word 'require do?  
  - require() imports the requested module.  
    ex: require('./count') // <----- This is saying we want the file in th current directory('./) then it looks for the file name ('./count)  
4. What do we have to do to make a module available?  
  - What path of the module that we want to make available to all of the files that require this specific module... using   
     module.exports = counter;   <------ This is making ***counter*** available outisde of its own module. THEN ***counter*** can be available by using var counter = require('./count')  
     - Make sure the variable you set for ***require*** is a name that references your module.exports module. 