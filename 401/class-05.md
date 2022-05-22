# Linked List
--  -
Source:[Linked List](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html) , [What's a Linked List?](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
        

A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a  
Linked List is that each Node references the next Node in the link.

There are two types of Linked List - Singly and Doubly. 

    Singly: refers to the number of references the node has. A Singly linked list means that there is only one reference,  
    and the reference points to the Next node in a linked list.  
    
    Doubly: refers to there being two (double) references withing the node. A Doubly linked list means that there is a  
    reference to both the Next and Previous node. 

    Node: Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.  
    
    Next: Each node contains a property called Next. This property contains the reference to the next node.  
    
    Head: The Head is a reference of type Node to the first node in a linked list.  
    
    Current: The Current is a reference of type Node to the node that is currently beiing looked at. When traversing,  
    you create a new Current variale at the Head to guarantee you are starting from the beginning of the linked list. 

Linked Lists are LINEAR DATA STRUCTURES, meaning there is an order and a sequence on how they are structured. 

The Head of a Linked List is the entry point and the End of a Linked List is not a node but more of a Node that POINTS  
to null/empty value. 

A node only knows about what data it contains and who its neighbor is. 