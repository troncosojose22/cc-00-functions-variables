# Code Challenge: Functions and Console.log vs Return

## Instructions

1. Create a folder in your `Development` directory called `code-challenges`. Inside of the `code-challenges`, create a directory called `unit-0`
2. Clone down this assignment to your `unit-0' directory.
3. Code your solution using JavaScript in `index.js`.
4. **Be sure to run and test your code throughly!**
5. By the end of Code Challenge, **commit and push your changes up to Github**.
6. Using the browser, verify that your solution is in your remote repo on Github.

### Instructions:

Answer the following questions in this markdown file

## Questions

1. What is the difference between `console.log` and the `return` statement? In your response be sure to answer the following:
    1. What is `console.log`?
    2. How is the `return` related to functions in JavaScript?
    
2. In this code snippet, what is the **argument** and what is the **parameter**?
    
    ```
    const sayHi = (name) => {
      return "Hi" + name
    };
    
    sayHi("fellows");
    
    ```
    

1. What is printed to the console, when the function `sayHi` is *invoked*?
    
    ```
    const sayHi = (name) => {
      console.log(name)
      return "Hi" + name;
    };
    
    sayHi("fellows");
    
    ```
    
2. Run this code in a file, what does the variable `hello` *evaluate* to? Why does it evaluate to this?
    
    ```jsx
    const hiFunc = () => {
      console.log("hi");
    };
    
    const hello = hiFunc();
    
    ```
    
3. What is the difference between `let` and `const`? What is the best practice when choosing which keyword to declare a variable with?
