# Debugging

## Order of Execution  
    - It is very important to organise your code properly in the correct order.  
      Some tasks cannot complete until another statement or function has been run. 


## Execution Context (pg. 453)
   JavaScript has an interpreter that uses the context of *execution contexts*  
      
      - Global Context: Code that is in the script but not in the function   
      - Function Context: Code that is being run in the function. 
      - Eval Context: Text is executed like code in an interanl function called " eval() " 

## The Stack (pg. 454)   
    - When a statement needs data from another functio, it stacks (or piles) the new function on top of the current task. 
    - When a statement has to call some other code in order to do its job, the new task goes to the top of the pile of thngs to do. 
    - Once the new task has een performed, the interpreter can go back to the task in hand. 

## Execution Context & Hoisting (pg. 456)
   There are two phases of activity when a script enter a nw execution context:  
    
       2. Prepare:
        - The new scope is created.
        - Variables, function, and arguments are created.
       
       1. Execute: 
        - Can assign values to variables.
        - Reference function and run their code.
        - Execute statements. 

## Understanding Scope (pg. 457)
    - Functions in JavaScript are said to have lexical scope
      They are linked to the object they were defined within. 
    - For each execution context, the scope is the current execution context's variables object,   
      plus the variable object for each parent execution context.


## Understanding Errors (pg. 458)
    - When ever a JavaScript statement generates an error, thn it throws an exception.   
      At that point, the interpreter stops and looks for exception-handling code. 
    - If you are anticipating that something in your code may cause an error, you can use a set of statements to **handle** the error. 
      This is important because if the error is not handled, the script will just stop processing and the user will not know why. 
