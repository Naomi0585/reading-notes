# React and Froms 

## Using Forms in React: 

A **Controlled Component** in React is an input element whose value is controlled by React **State** instead of the browser's internal DOM state. 

* We should use the state as soon as the user types into the form. This lets React always know the current input. 
* We target what the user is typing by using the *event* object to identify what input field changed. 

## The Conditional (Ternary) Operator: 

We use **Ternary** operator as a shorter and cleaner way to write simple `if/else` statements. 

<u>Rewrite the following statement using a ternary statement:</u>

```javascript
if(x===y){
  console.log(true);
} else {
  console.log(false);
}

```
Answer: 
```javascript
x === y ? console.log(true);  console.log(false);