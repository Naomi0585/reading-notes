# JavaScript Call Stack

In JavaScript a *call* is when a one function is executed or invoked in a program. When a function is called, JavaScript adds it to the call stack and beggins running it's code. It's important to know that only one call can be executed at a time in the call stack because JavaScript is **single-threaded**. Other function calls must wait their turn on the stack.  
Another important concept is **Stack Overflow** which happens when there are too many function calls on the call stack, causing it to exceed it's maximum size. In this case the function will be stuck in a repetitive loop. 

## LIFO

When we say that the call stack operated by the data structure principle of **Last in, First out,** it means that the last function gets pushed into the stack is the first to be popped out, when the function returns. 

```Javascript

function first(){
    second();
}

function second(){
    third();
}

function third(){
    console.log("Hello!");
}

first();
```

* `first()` is called and pushed onto the stack.
* `first()` calls `second()`, so `second()` is pushed on top.
* `second()` calls `third()`, so `third()` is pushed on top.
* After `third()` finished, it is removed first, then `second()`, then `first()`.

## JavaScript Error Messages 

* `Reference Error` - This is as simple as when you try to use a variable that is not yet declared. You might get this type *OS* error: 

```
 console.log(foo) // Uncaught ReferenceError: foo is not defined
```
This is also a common thing when using `const` and `let`, they are hoisted like *variable* and *function* but there is a time between the hoisting and being declared so when you try to access them a reference error occurs. 

* `Syntax Error` - This occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using *JSON.parse*. Some syntax errors like sending a trailing comma when calling a function are handled without error by most recent browsers. 

* `Type Error` - These types of errors show u when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an *undefined* type of variable. This probably is the most frequent error in JavaScript. 

## Breakpoing and Debbuging 

A **Breakpoint** is a place in your code where execution pauses so that you can inspect variables, the call stack, and the current state of the program while debugging. 
A **debugger** keyword tells JavaScript to pause execution at the line if the browser's developer tools are open. This allows you to inspect variables and step through your code line by line. When the code reaches **debugger**,  the execution pauses so you can examine the prgram's state. 