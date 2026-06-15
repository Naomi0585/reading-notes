# Functional Programming 

Functional Prgramming is a programming paradigm (a style of building the structure and elements of computer programs) that treats computations as evaluations of mathematical functions and avoids changing state and mutable data. 

## Pure Functions

Pure funtions can be Identified when they return the same result if given the same areguments (also known as *deterministic*). Pure functions don't cause any observable side effects. Pure functions are stable, consistent and predictable. Given the same parameters, pure functions will always return the same result, making the code easier to test. 

## Immutability

When data is immutable, its state cannot change after it's created. If you want to change an immutable object, you can't. Instead, you create a new object with the new value. 

## Referential Transparency 

If a function consistently yields the same result for the same input, it is referentially transparent. 

`pure functions` + `immutable data` = `referential transparency` 


### Modules and Require: 

A modules is a file that contains code (such as variables and functions) that can be reused in other files. Modules help organize code and keep it manageable. To make a module available we must export the functions, variables or objects we want other files to use by using: `module.exports`. 

`require` is used in `Node.js` to import a module into the current file so that you can use the code it exports. We use `require()` as a function to bring another module into the file we are working in. We would provide the path to the module inside the parenthesis. 