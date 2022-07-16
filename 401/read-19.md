# Reading Notes
## Functional Programming

### Difference between pure and impure functional programming

A program is usually said to be functional when it uses some concepts of functional programming, such as first-class functions and higher-order functions.  

However, a first-class function need not be purely functional, as it may use techniques from the imperative paradigm, such as arrays or input/output methods that use mutable cells, which update their state as side effects.  

In fact, the earliest programming languages cited as being functional, IPL and Lisp, are both "impure" functional languages by Sabry's definition.

Purely functional data structures are persistent. Persistency is required for functional programming; without it, the same computation could return different results. Functional programming may use persistent non-purely functional data structures, while those data structures may not be used in purely functional programs.