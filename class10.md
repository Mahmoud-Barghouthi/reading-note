### Errors and Debugging

### ORDER OF EXECUTION 
#### The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:

Function greetUser() {
    return 'Hello' + getName();
}

Function getName() {
    let name = 'Mahmoud';
    return name;
}

#### This script above creates a greeting message, then writes it to an alert box (see right-hand page). In order to create that greeting, two functions are used: greetUser () and getName () . 

### EXECUT.ION CONTEXTS 
#### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

### EXECUTION CONTEXT & HOISTING
#### Each time a script enters a new execution context, there are two phases of activity:
##### 1. Prepare
##### 2. Execute

#### UNDERSTANDING SCOPE
#### In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.

### UNDERSTANDING ERRORS 
#### If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handl ing code. 

### ERROR OBJECTS 
#### Error objects can help you find where your mistakes are and browsers have tools to help you read them. 

### HOW TO DEAL WITH ERRORS
1. Debug the script to fix errors
2. HANDLE ERRORS GRACEFULLY 

### A DEBUGGING WORKFLOW
#### Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be,then look for clues.

### BROWSER DEV TOOLS & JAVASCRIPT CONSOLE
#### BROWSER DEV TOOLS & JAVASCRIPT CONSOLE

### HOW TO LOOK AT ERRORS IN CHROME
 