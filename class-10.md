# Js Debugging




**Debugging** is the process of finding errors and then fixing them. 
There is a possibility to make mistakes when writing the JavaScript code so then errors will appear.

**Order of execution**: some tasks cannot complete until another statement or function has been run

**Execution context** : 
Every statement in a script lives in one of the execution contexts:
 1- GLOBAL CONTEXT
Code that is in the script, but not in a function.
There is only one global context in any page.
 2- FUNCTION CONTEXT
Code that is being run within a function, so each function has its own function context. 

**The stack** : Js interpreter process each line at a time so when a statement needs data from another function it stacks or piles the 
new function on the top of the current statement.

**Execution context & Hoisting**
Each time a script enters a new execution context, there are two phases of activity :
- Prepare
- Execute

**Error objects** can help you find where your mistakes are and browsers have built-in tools to help you read them. When an error object is created it will contain these properties:
- name (type of exexution)
- message (description)
- file number (javascript file)
- line number (line of error)
So when there is an error you will see these properties inside the console of the browser.
There are seven types of built-in error objects:
- Error ( is the template from which all other error objects are created)
- Syntax Error (syntax)
- NAN (not a number)
- Generic error
- ReferenceError (variables, functions)
- TypeError (objects, methods)
- Range Error (numbers)
- URI Error (special characters not escaped in the url)
- EvalError (eval() function is incorrect)

**How to deal with errors?**
1- Debug the script to fix errors.
2- Handle errors gracefully (using try, catch, throw, and finally statements).

