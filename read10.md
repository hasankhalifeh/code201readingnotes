# Chapter 10 Error Handling and Debugging:
    - Javascript can be annoying to learn and everyone makes mistakes when writing it, we will focus more on figuring out solutions and tips in finding errors in our code. 
    - To the find the soruce of error it helps to know how scripts are processed, the other of which statements are executed can be complex. 
    - The JS uses interpreter uses the concept of execution contexts. There is one global execution contxt, which each function creates a new execution contect. There are Global context, function context, eval context under execution context. And under variable scrop are global scopr and function level scope. 
    - The js interperter processes one line of code at a time, when a statement needs data from another function it stacks the new function on top of the current task. 
    - Execution Context and hoisting:
        - Each time a scripts enter a new execution context there are two phases of activity: 
            1. Prepare: 
                - Where a new scope is created
                - Variables,functions and arugruments are created. 
                - The value of the this keyword is determined/
            2. Execute:
                - Now it can assign values to variables.
                - Reference functions and run their own code. 
                - Execute statements. 
    
    - Functions in JS are said to have lexical scope. They are linked to the object and they where defines within. 
    - If JS statements generates an error then it throws an exception, at that point we stop and look for exception handling codes. 
    - Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
    - How to deal with errors:
        1. Debug the script to fix errors, you will have to basically track the source of the error and fix it. 
        2. Handle errors gracefully, you can handle errors using try,catch,throw and finally statements. When you set breakpoints you can see if the varibale around them have values. Break down or out parts of the code to test smaller pieces. 
    - Grouping messages:
        - If you wana write a set of related data you would use console.group().You can then expand and contract the restults. 
        - When you finish writing out the reulst for the group you end the group with console.groupEnd(). 
    - Writing on a condition, using the console.assert() you can test if a condition is met. 
    - Breakpoints, you can pause the execution of a script on any line using breakpoints. If you set multiple break points you can step through them one by one where values change and a problem might occur. 
    - Conditional breakpoints, you can indicate that a breakpoint should be triggered only if a condition that you specify is met. 
    - You can create a breakpoint using the debugger keyword, when the developer tools are open this will automatically create a breakpoint.
    - If your code might fail use try,catch and finally.
    - Debugging tips:
        - Using another browser
        - Add numbers: write numbers to the console so you can see which are the items.
        - Searching for it online looking at stack overflow.
        - Validation tools there are number of tools online.
        - Code playgrounds, you can use online coding forums to ask and looking at other codes that solved yours. 
        - Strip it back, remove parts of your code to see where the errors are. 
        - Js has 7 different types of errors, each one creates its own error object and it tells you its line number 