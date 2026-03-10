# HTML Tables and JS Constructor Functions 

## Object-Oriented Programming, HTML Tables 

Domain modeling helps us clearly understand and organize how *real-world* systems works before it's built into the code. A **Domain Model** acts like a plan or map for your program. 
When you clearly define the data that exits and the rules that apply, bugs and errors are preventable. Domain modeling bridges the gap between *real-world* problems and programming solutions. 

### Intro to Constructors: 
A **Constructor** is a special function used to create multiple objects with the same structure. Constructors start with a capital letter and ore named for the type of object they create. 

<u>**Advantages of Using Constructors:**</u>

Some advantages of using constructors are their reusability, you only have to define a structure once in your program and that way you don't have to repeatedly rewrite them. Constructors will make your code look cleaner and make it readable. Also, constructors work great with domain modeling! 

* In an <u>object literal</u> `this` refers to the object itself but in a <u>constructor function</u>, `this` refers to the new object being created when the constructor is called with `new`.

### HTML Table Basics: 
 
 For starters, a table is a structured set of data made up of rows and columns. The point of a table is that is is rigid. Information is interpreted easily by visial associations. In HTML tables should be used to tabular data as they were designed for. Although, tables shouldn't be used for layouts since using them could reduce assecibility for visually impaired users. 
 Tables in this clase could also cause a *tag soup* and then the code becomes hard to work with overall. Finally, tables in this case would not automatically respond. 

 
 | `<th>`| `<td>` | `<tr>` |
|----------|----------|----------|
| *table reader*    | *table data*    | *table row*    |
| These go at the atart of a row or column and define the type of data the row or column contains.   | Smallest container inside a table. creates a single cell and makes up the first row.   | These stop rows from growing and start placing subsequent cells on a second row. 

## Object Prototypes Using a Constructor

When I was making my About Me page, I can think of prototypes and inheritance like using a base template for multiple sections of the website.
The prototype is like the main template or style I created for the page. For example, I might make a general layout for sections with the same font, spacing, and colors. That template acts as the starting point and almost guide to follow for the rest.

Inheritance is when other parts of the page automatically use that same structure or style. For example, the sections about my hobbies, background, and goals could all inherit the same layout from the main template. If I update the template, the other sections follow that change without me having to rewrite everything.   |