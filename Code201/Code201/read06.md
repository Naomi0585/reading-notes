# Domain Modeling, Intro to the DOM, and Object Literal Notation

An **Object** is a collection of related data and/or function. These usually consist of several variables and functions, which are called *properties* and *methods* when they are inside an object. For example, think of an object as a backpack and the contents inside that backpack as the *properties* and *methods*. 

An object that contains members that are functions is known as an **Object Literal**. It;s very common to create an object using an object literal when you want to transgfer a series of structured related data items in some manner. For example, sending a request to the server to be put into a database. 
Creating object literals keeps related data organized, is easy to read since it's structured better and is very flexible. 

## Arrays and Objects

* An **array** is a numbered list that uses numbers.An **object** is a labeled container that uses labels and is not based on a position or numbers. An object is best used for descriptions. To access an array you use numbers and to access and object you do so by name. 

## Literal Notations

**Bracket notations** provide alternative ways to access object properties. Instead of using **Dot notations**, you use an index number to select an item and use the name associated with each member's value. You would use bracket notation instead of dot notation when the property name has spaces and when the property name is stored in a variable. 

### valuate the code below. What does the term `this` refer to and what is the advantage to using `this`?

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

* `this` refers to the `dog`. When a function is called as a method of an object, `this` refers to the object before the dot, in this case it would be `dog`. 

## Intro to the DOM 

The Document Object Model, better known as **DOM** is a programming interface for web documents. The **DOM** connects web pages to script or programming languages by representing the structure of a document. The **DOM** represents a document with a logical tree. A **DOM** tree is a tree structure whose nodes represent an HTML or XML document's contents. Each branch ends in a node and each node contains objects. 

* The **DOM** is the browser’s structured representation of an HTML page, organized like a tree of elements. **JavaScript** interacts with the DOM to read, modify, add, or remove content and respond to user actions. In short, the *DOM* represents the webpage, and *JS* uses it to make the page dynamic and interactive.