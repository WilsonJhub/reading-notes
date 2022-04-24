# Readings: In Memory Storage  
_____________________________


## Understanding the JavaScript Call Stack  

1. What is a 'call'?   
  - A call stack is a data structure that uses the Last in, First Out (LIFO) principle to temporarily store and manage function invocation (call)
  - A *call* is what happens when a function needs to be executed. We only *call* a function when we are ready for its specific function to run. 
  - First, we 'set and define' the function. Then, we *call* the function. 
2. How many 'calls' can happen at once?  
  -  One. The call stack maintains a record of the position of each stack frame. It knows the next function to be executed (and will remove it after exectution). This is what makes code execution in JavaScript synchronous
3. What does LIFO mean?  
  -  Last In, First Out.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.  
  -  
5. What causes a Stack Overflow?  
  - A stack overflow occurs when there is a recursive function (a function that calls itselft) without an exit point.  

## JavaScript Error Messages  

1. What is a 'reference error'?   
  - Using a variable that has not been declared will cause a ***reference error***  
2. What is a 'syntax error'?  
  - Occurs when something that cannot be parsed in terms of syntax.  
3. What is a 'range error'?  
  - When trying to manipulate an object and giving it an invalid length. (hence the word ***range***)  
4. What is a 'type error'?  
  - This will happen when *types*(number, string, etc.) you use are incompatible,  
    like accessing a property in an undefined type of variable. 

