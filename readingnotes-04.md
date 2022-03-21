# ***HTML Links, CSS Layout, JS Functions.***  
 
 

## Links (pg. 77)

Links are created using the <a> element. Users can click on anything between the opening `<a>` and the closing `</a>` tag. You specify which page you want to link to by using the (href) attribute. 
     
     Ex:   
           `<a href="http://www.imdb.com">IMDB`</a>`
  The text between the `<a>` tag and the closing `</a> tag is know as link text. This should tell the visitor where they will be taken to. 
  

## Layout(pg.361)

**CSS treats each HTML elements as if it is in its own box. This box will either be a block-level box or an inline box.** 
  * Block-Level Boxes: start on a new line and act as the main building blocks of any layout.  
  * Inline Boxes: Flow between surrounding text.    

**CSS has 3 position schemes that allow you to control the layout of the page.**  
  
  * **Normal Flow:**  Every block-level element appears on a new line, causing each item to appear 
      lower down the page than the previous one. Even if you specify the width of the boxes and 
      there is enough space for two elements to sit side-by-side, 
      they will not appear next to each other unless you tell it otherwise.  
 
      
       
  
  * **Relative Positioning:** This moves an element from the position it would be in normal, shifting it to the top, right, bottom, or  
      left of where it would have been placed. This does not affect the the position of surrounding elements; 
      they stay in the position they would be in in normal flow.
    
         Ex: 
              p.example {
                position:relative;
                top: 10px;
                left: 100px;
              }
   
  
  * **Absolute Positioning:**  This positions the element relation to its containing element.  
      It is taken out of normal flow, meaning that it does not affect the position of any 
      surrounding elements(as they simply ignore the space it would have taken up). 
   ***Absolutely positioned elements move as users scroll up and down the page.*** 

## **Functions, Methods, and Objects**(pg. 88)

#### ***IMPORTANT:***  
--------------------------
Browsers require very detailed instructions about what we want them to do. Therefore, complex scripts can run to hundreds (even thousands) of lines. Programmers use functions, methods, and objects to organize their code.  
--------------------------  
* Functions: Consist of a series of statements that have been grouped together because they perform a specific task.  
A method is the same as a function, except methods are created inside (and are part of) an object.
* Objects: Used to create models of the world using data and are made up of properties and methods.
* Built-in Objects: The browser comes with a set of objects that act like a toolkit for creating interactive web pages. 

 
 To create a function, you give it a name and then write the statements neede to achieve its tast inside the curly braces. This is known as a function declaration.  
 
