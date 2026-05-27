# Thinking in React 

## React Docs 

### The Responsability Principle

 The simple responsability principle means that each component should have **one** clear purpose. It implies that one component should only be handling one task, so it's easier to test later. 

 #### Static 

 To build a static version of your app that renders your data model, you'll want to build *components* that reuse other components and pass data using *props*. 
 After building your components, you'll have a library of reusable components that render your data model. Because this is a static app,the components will only return JSX. The component at the top to the hierarchy will take your data model as a prop. This is called *one-way data flow*.

 ##### Determining State

* Does it remain unchanged over time? 
* Is it passed down from a parent via props? 
* Can you compute it based on existing state or props in your component? 

After determining your app's minimal state data, you need to identify which component is responsible for changing this state, or owns the state. Often, you can put the state directly into their common parent. If you can't find a component where it makes sense to own the stae, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component. 

## Higher-Order Functions: 

Functions that operate on other functions, either by taking thrme as arguments or by returning them, are called *higher-order functions*. These type of functions allow us to abstract over actions, not just values and they come in several forms. 

`greaterThan`

```javascript 
function greaterThan(n) {
  return m => m > n;
}
``` 

* This function takes a number (m) and checks if it's bigger than (n). The new function remembers the value of `n` from when `greaterThan` was called. In line 2, a new function is returned that compares a value (m) to (n) and returns `true` if `m` is greater than `n`. It remembers `n` from the original function call. 

`map` 

* This method transfroms an array by applying a function to all of it's elements and building a new array from the returned values. The new array will have the same length as the input array, but it's content will have been *mapped* to a new form by the function. 

`reduce` 

* This method, sometimes also called `fold`, builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you'd start with the number zero and, for each element, add that to the sum. The parameters to `reduce` are a combining function and a start value.