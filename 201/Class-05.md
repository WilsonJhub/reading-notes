# Images 
 
 ### Why do I need an image?
    Great images will elevate your webpage and add life to it.  
    You don't want to have a website full of text and empty of pictures. 
    
  ### Storing Images(pg. 98)
    When building a site from scratch, it is good practice to create a folder  
    strictly for your images used on your webpage and subfolders when you expand it!

  ### Adding Images (pg. 99)
      The <img> element is used to add an image to your page.  
      Becuase <img> is an empty element and does not need a closing tag, it needs to two of the following attributes:
          - src: Informs the browser where to locate the image file. 
          - alt: Provides a text description of the corresponding image. 
  #### title can also be used within the <img> text to provide additional information to an image. 

          Example:
            - <img src="images/quokka.jpg" alt="Text description of image" />

  ### Height and Width
      Often times you will see height and width added to an image to provide added modifications. 
        Example: 
            - <img src="location of image" width="300" height="300" />

  ### Where to Place an Image in Your Code
    1. Before a paragraph
      - That paragraph starts on a new line before your image. 
      Example:
          <img src= "images/bird.gif" alt="bird" width="300" height="100" />
        <p> Sample text of where I would enter information of the image placed *ABOVE* this paragraph</p>

    2. Inside the start of a paragraph
      - The first row of text aligns with the bottom of the image. 
      Example:
          - <p> <img src= "images/bird.gif" alt="bird" width="300" height="100" />) Sample text of where I would enter 
            information of the image placed at the *START* of this paragraph</p>

    3. In the middle of a paragraph. 
     - The image is placed between the word of the paragraph that it appears in. 
     Example:
          - <p>Sample text of where I would enter <img src= "images/bird.gif" alt="bird" width="300" height="100" /> information of the image placed at the *WITHIN* this paragraph
### Aligning Images(Top, Middle, Bottom, Left, Right)
    Example:
      - <img src= "images/bird.gif" alt="bird" width="300" height="100" align="left" />
    Example:
      - <img src= "images/bird.gif" alt="bird" width="300" height="100" align="right" />
    Example:
      - <img src= "images/bird.gif" alt="bird" width="300" height="100" align="top" />
    Example:
      - <img src= "images/bird.gif" alt="bird" width="300" height="100" align="bottom" />
      Example:
      - <img src= "images/bird.gif" alt="bird" width="300" height="100" align="middle" />

  
# Colors 
  *Color is another great way to add some emphasis to your website.*

  ### RGB Values(pg.249)
    - These tell the user how much red, green and blue, colors being used in order to select the desired color 
      Example:
        - rgb(50,50,50)

  ### Hex Codes(pg.249)
    - Hex codes are six-digit codes that state the value of a color by referencing red, green, and blue.
      Example:
        - #ee3e80

  ### Color Names(pg.249)
    - There are a total of 147 predifined color names that are recognized by a browswer. 
      Example:
        - Dark Red

        Code Example: 
          - h1 {
            color: DarkRed;}

