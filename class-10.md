# JavaScript book, Ch. 10, “Error Handling & Debugging”

* order of execution is one of the methods in javascript to find errors and fix them. this method particulary finds the source of the error and fix it, because in javascript some tasks cannot be completed until other statments and function has been run correctly. 

* execution contexts is a concept that javascript uses and correspond to variable scope. there are three types of execution context. 

1) Global context. 2) Function context. 3) Eval context.

* there are two types of variable scope in which the execution of context correspond too. 

1) The global scope . 2) The function-level scope.

**Tha stack** 

which is a linear data structure that is used to store the collection of objects. it is used when a statment needs data from another function, so it piles the new function on top of the current task where the new task set at the top of the stak. so once the new task has done its job, the developer can go back to the previous task. 

![image](https://static.javatpoint.com/core/images/java-stack.png)

* execution context & hoisting: there are two phases of activity 1) PREPARE: (the scope and arguments are created and the values are determined) 2) EXECUTE: (variables are assigned to values ans statments are executes). when these two phases are completed, which means the functions and variables are created before they are executed we can **hoist** them to the top of the execution context. 

* each execution context has its own variables objects with ability to access its parents's vriable s objects. the lexical scope that the functions have are linked to the objects they were define within. the scope is the current execution context's variables object. 

* in javascript, if a statment generate an error, it throws an exception. at this point the developer stops and looks for the exception. Error objects help you fine where the mistake in your code.

![image](https://media.geeksforgeeks.org/wp-content/uploads/Exception-in-java1.png) 

* There are two things the developer can do when dealing with errors. 1) Debug the script to fix errors. 2) Handle errors gracefully. 

* Debugging eliminate the potential causes of an error. it help you to determine where the problem is and narrow down the area where the problem seems to be. and check how far the script is running and use breakpoints where things are going worng. then, once the problem is located the debugging tells you what exactly the problem is by checking the set of the breakpoints, you can then check the numbrs of parametrs for a function or the number of items is array.