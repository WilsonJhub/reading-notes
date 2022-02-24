# JavaScript Notes

## Control Flow
 - The Contro Flow is the order in which the computer executes statements in a script

 ## Conditional Structure
  - Scripts will analyze data on a webpage to determine its value. In order to validate the data. If a user lave a required field empty, the script prompts them to fill it in.
        to do this, the script uses Conditional Structure.
        #### Example:
            - if (field==empty) {
                prompt user();
            } else {
                submitForm();
            }

## Loop
    - A loop is a sequence of instrucitons that is continually repeated until a certain condition is met in computer programming. 
        Example: When you do not check the "I accept the terms and conditions", you cannot proceed to the next page. 
    Syntax:
         - for (statement 1; statement 2; statement 3){
             execute code block
         }
                Example:
                    for(var i = 0; i < 10; i++){
    console.log(i)
}
//This loop will print numbers 0-9, will stop when condition is met (i = 10)


##  Function 
    - A function is a code snippet that can be called by other code or by itself, or a variable that refers to the function.
 ### Different Functions
  - Anonymous Function  - Recursive Function
  - Named  Function     - Immediately Invoke Function Expressions
  - Inner Function      

  Anonymous Function 
    - a function without a function name. 
        - Example: 
         // When used as a function expression
         (function () {});
         // or using the EXMAScript 2015 arrow notation 
         () => {};

 ### Named Function 
    - A function with a function name. 
        - Example:
            // function declaration
            function foo() {};
            // Named funtion expression
            (function bar() {});
            // or using the ECMAScript 2015 arrow notation
            const foo = () => {};

### Immediately Invoked Function Expression
    - a function that is called directly after the function is loaded into the browser's compiler. The way to identify an IIFE is by locating the extra left and right parenthesis at the end of the function's definition.
        - Example:
            // Declared functions can't be called immediately this way
            // Error (https://en.wikipedia.org/wiki/Immediately-invoked_function_expression)
            /*
            function foo() {
            console.log('Hello Foo');
            }();
            */

            // Function expressions, named or anonymous, can be called immediately
            (function foo() {
             console.log("Hello Foo");
            }());

            (function food() {
            console.log("Hello Food");
            })();

            (() => console.log('hello world'))();
