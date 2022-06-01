# Stacks and Queues
***source:*** 
[Stacks and Queues](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)
-- -
## ***What is a Stack?***
- *A stack is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not  
  reference its previous Node.*   
-- -

***Common Terms:***
1. ***Push:*** Nodes or items that are put into the stack are pushed  

2. ***Pop:*** Nodes or items that are removed from the stack are popped. When you attempt to pop an empty stack an  
      exception will be raised.  
3. ***Top:*** This is the top of the stack.  

4. ***Peek:*** When you peek you will view the value of the top Node in the stack. When you attempt to peek an empty stack an exception will be raised.

5. ***IsEmpty:*** returns true when stack is empty otherwise returns false.  
-- -
***FILO:***  
- This means that the first item added in the stack will be the last item popped out of the stack.  

-- -
### Stack Visualization

*Here’s an example of what a stack looks like. As you can see, the topmost item is denoted as the top.  
When you push something to the stack, it becomes the new top. When you pop something from the stack,  
you pop the current top and set the next top as top.next.*  

![Stack Visualization](D:\401-Java\401\reading-notes\pictures\stack1.png)