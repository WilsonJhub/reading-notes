# CSS Layout 


## Display Property
  - The <display> property determines if the box that it is applied to is a block or an inline.
    - Inline Elements: are used to style text within a <p> and preserve surrounding whitespaces. 
  
  ### Block elements
    - Block elements create a new line for themselves. Block elements will expand to the inline dimenstion, therefore spanning the full width in a orizontal writing mode. 
      Example:
          .my-element {
	          display: block;
}
       - The display property also determines how an element's children should behave. For example, setting the display property to display: flex makes the box a block-level box, and also converts its children to flex items. This enables the flex properties that control alignment, ordering and flow. 

  
  ### Flexbox and Grid
    - There are two main layout mechanisms that create layout rules for multiple elements, flexbox and grid.
        Example:
        .my-elemnt {
          display: flex;
     }
     
     Flexbox is a layout mechanism for one-dimensional layouts. Layout across a single axis, either horizontally or vertically.


     Sources: https://web.dev/learn/css/layout/