# Object-Oriented Programming, HTML Tables

## Domain Modeling

Domain Modeling: the process of creating a conceptual model in code for a specific problem.  
A model describes the various entities, their attributes and behaviours, as well as the constraints that govern the problem doamin. 

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders.  
As a communication tool it can be used within and between both technical and usiness teams.

### Defining a Constructor and Initializing Properties

  Constructor functions are defined using a *function expression*. Variables are declared and then assigned a function with parameters. 
  
  When a function is called, the date held inside of the parameters are stored inside the *this.____* properties.  
  Storing data within properties ensures any newly created object can acces that data later. 

  AFTER the constructor *function definition*, obect(s) are ***instantiated*** with the **new**  keyword and their properties are initialized by calling the ***constructor function***. After being instantianted and initialized, these objects are stored inside the previously defined variable.

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from outside.
* Use the this variable within methods so you can access the object's properties and methods from inside.


