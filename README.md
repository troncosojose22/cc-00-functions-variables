# Code Challenge: Functions and Console.log vs Return

## Instructions

1. Create a folder in your `Development` directory called `code-challenges`. Inside the `code-challenges` directory, create another directory called `unit-0`
2. Clone down this assignment to your `unit-0' directory.
3. You can run and code JavaScript in `index.js`.
4. **Be sure to run and test your code thoroughly to answer the questions correctly!**
5. By the end of Code Challenge, **commit and push your changes up to Github**.
6. Using the browser, verify that your solution is in your remote repo on Github.

### Instructions:

Answer the following questions in this markdown file. You can use the `index.js` file to run and test code. If you would like to format your answers using Markdown, reference this [Markdown guide](https://www.markdownguide.org/basic-syntax/). 

## Questions
1. In this code snippet, what is the **argument** and what is the **parameter**?
    
    ```jsx
    const sayHi = (name) => {
      return "Hi" + name
    };
    
    sayHi("fellows");
    
    ```
    
2. What is the difference between `console.log` and the `return` statement? In your response, be sure to answer the following:
    1. What is the purpose of `console.log` What is the purpose of `return`?
    2. How is the `return` related to functions in JavaScript?
   
3. What is printed to the console, when the function `sayHi` is *invoked*?
    
    ```
    const sayHi = (name) => {
      console.log(name)
      return "Hi" + name;
    };
    
    sayHi("fellows");
    
    ```
    
4. Run this code in a file, what does the variable `hello` *evaluate* to? Why does it evaluate to this?
    
    ```jsx
    const hiFunc = () => {
      console.log("hi");
    };
    
    const hello = hiFunc();
    
    ```
    
5. What is the difference between `let` and `const`? What is the best practice when choosing which keyword to declare a variable with?
