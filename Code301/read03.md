# Passing Functions as Props 

##  <u>React Docs - Lists and Keys </u>

What are the return properties of `map()`? 
* It returns a new array with each element being the result of the callback function. 
* You will probably rely on JS features like `for` loop and the `map()` array function to render lists of components. Inside your component, use the `map()` function to transform an array into an array of `<li>` items. 

**Each list item needs a unique KEY.**

* React uses **keys** to know what happened if you later insert, delete or reorder the items. 

## <u>The Spread Operator</u>

The *Spread* (`...`) operator allows an iterable, such as an array or string, to be expanded in places where zero or more arguments or elements are expected. In an object literal, the spread operator enumerates the properties of an object and adds the key value pairs to the object being created. 

### Functions of a Spread Operator:
- Copy arrays
- Combine arrays
- Add arrays 
- Combine objects 

### ★ Combining Arrays ★

```javascript
const arr1 = [3,8];
const arr2 = [4.9];

const combine = [...arr1, ...arr2];

console.log(combine);
//[3,8,4,9]
```

### ★ Adding Arrays ★

```javascript
const animals = ['Cat', 'Giraffe'];
const justAnimals = [...animals, 'Zebra'];

console.log(justAnimals);
//['Cat', 'Giraffe', 'Zebra']
```

### ★ Combining Objects ★

```javascript
const obj1 = {foo: "bar" x:42};
const obj2 = {bar: "baz", y:13};

const combine obj = {...obj1, ...obj2};
//{foo:"bar", x:42, bar:"baz", y:13}
```

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=n-6i_WGIOKE)

### NOTES: 
* From the previous video; the first step the developer makes to pass functions between components is to create the function in the parent component and then pass it down as a `prop` to the child component. 
* The `handleClick` function responds to a user action and usually changes, updates or triggers data behavior. 
* A method from a parent component can be passed into a child component by sending the function through `props`. 
* A child component invokes a method passed from the parent component by calling the function from `props` inside an `onClick` event. When the button is clicked the parent function runs. 

