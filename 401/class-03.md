# Class 03

-- -

## **Primitives vs. Objects**

### ***Java Type System***   

Source: [Java Primitives vs. Objects](https://www.baeldung.com/java-primitives-vs-objects)

    - Java has a two-fold type system consisting of primitives such as int, boolean and reference types such as  
    Integer, Boolean. Every primitive type corresponds to a reference type.  
    The wrapper classes are immutable (so that their state can't change once the object is constructed)  
    and are final (so that we can't inherit from them). Under the hood, Java performs a conversion  
    between the primitive and reference types if an actual type is different from the declared one:

    - The decision what object is to be used is based on what application performance we try to achieve,  
    how much available memory we have, the amount of available memory and what default values we should handle.
    If we face none of those, we may ignore these considerations though it's worth knowing them.
    
    
