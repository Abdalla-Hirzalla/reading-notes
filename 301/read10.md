# In memory storage

# Call 

## What is a call?
The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous In Asynchronous JavaScript, we have a callback function, an event loop, and a task queue. The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.

## How many ‘calls’ can happen at once?

JavaScript is the single-threaded programming language. The JavaScript engine has only one call stack so that it only can do one thing at a time. When executing a script, the JavaScript engine executes code from top to bottom, line by line. In other words, it is synchronous.


## What does LIFO mean?

**LIFO:** When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.?

function greeting() {
   // [1] Some code here
   sayHi();
   // [2] Some code here
}
function sayHi() {
   return "Hi!";
}

// Invoke the `greeting` function
greeting();

// [3] Some code here

## What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.




# JavaScript error messages


## What is a ‘refrence error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.This is also a common thing when using const and let, they are hoisted like var and function but there is a time between the hoisting and being declared so when you try to access them a reference error occurs, the fact that this happens to let and const is called Temporal Dead Zone (TDZ).

## What is a ‘syntax error’?

I know it’s in the name of the errors, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.This can be solved by just fixing the syntax, in this case the object should be a JSON.

## What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

## What is a ‘type error’?

Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.This is probably the most frequent error in JS, trying to access a property/method thinking that bar is of the type object

## What is a breakpoint?

The Debugger Statements JavaScript Breakpoint will pause JavaScript execution whenever any debugger statement is executed if it's enabled. The All Exceptions JavaScript Breakpoint will pause JavaScript execution whenever any exception is thrown if it's enabled.

## What does the word ‘debugger’ do in your code?

Debuggers allow users to halt the execution of the program, examine the values of variables, step execution of the program line by line, and set breakpoints on lines or specific functions that, when hit, will halt execution of the program at that spot