# Read-10

##  Call stack :
`<call stack>` 
 is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.

Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.


When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.


If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

## Understanding the JavaScript call stack :

## LIFO:
 When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.


### Temporarily store:
 When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame. This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.

### What causes a stack overflow?
 A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.
 The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

### In summary
The key takeaways from the call stack are:
1. It is single-threaded. Meaning it can only do one thing at a time.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.
4. It works as a LIFO — Last In, First Out data structure.

## Types of error messages :
1. Reference errors
2. Syntax errors
3. Range errors
4. Type errors
5. Debugging
6. Call stack
7. Handling errors



[Main Page](https://thaerm94.github.io/reading-notes301)