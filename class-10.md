# 201 Class 10 Reading

## Debugging
Every code is going to have errors when it is first written. Maybe you fat fingered and entered two letter instead of one. You are probably missing a comma or a curly brackets in multiple places. Knowing how to debug your code is just as important as knowing how to code in the first place. And learning how to debug can help teach you more deeply how to code.  
when a piece of code does not work it is important to look at the order of execution, according to Jon Duckett in his book Javascript and JQuery on page 452.
>To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

Execution context must also be examined. there are two main kinds of execution context that we deal with.
* Global Context 
* function context
global context refers to any code that is inside the script but outside a function. global can be used by any other code. Function context refers to and code within a function that can only be used by that function unless it is placed outside the function giving it global functionality.  

When an error occurs in your code it creates an exception. After an error occurs the interpreter begins to look for some code that handles exceptions.  If you think a piece of code may cause an error it is good to write a code to handle the exception otherwise the code will no execute at all and it will be unknown to the user why it isn't working. 

### Error Objects
When you get an error you are often given an error object that tells you what the name of the error is, a brief description, the file number and the line number on the file.  There are 7 different types of error objects.
* Error-general error.
* SyntaxError- an error in a codes syntax.
* ReferenceError-when the code is trying to reference a variable that is not declared globally.
* TypeError- a date type that cannot be used in a certain instance.
* RangeError- when your numbers are not within a set range.
* URIError- incorrect use of URI functions.
* EvalError- incorrect use of the `eval()` function

[main](README.md)
