# Basics of HTML, CSS and JS

We must get used to **HTML, CSS** and **JS** as we will used them often as the basis of our website developing. As an introduction we must keep reviewing the elements of HTML. one of these are *semantic elements* which are very important in HTML since these apply emphasis and importance to text. These elements describe what the content is, making it's code easier to read and the page just better and more accessible overall for screen readers. 

## Important things to note about HTML:

* HTML contains 6 levels of heading. With **h6** or level 6 being the smallest heading and **h1** or level 1 being the largest. 
* `<sup>` = Superscript = Raises text.
* `<sub>` = Subscript = Lowers text.
* `<abbr>` Is used to wrap around an abbreviation or acronym. When including either, provide a full expansion of the term in plain text on first use, along with the `<abbr>` to markup the abbreviation. 

# Learning CSS

There are 3 different ways to apply **CSS** to an HTML document: 
1.  External Stylesheets 
2. Internal Stylesheets
3. Inline Styles 

### NOTE! 
* **Inline Styles** should be avoided since it's the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Also, *Inline* CSS mixes presentational code with HTML and content, making everything more difficult to read and understand. 

#### Examples of reading code: 
   `h2 {

     color: black;
     padding: 5px;
   }`

   1. What is representing the selector? **h2**
2. Which components are the CSS declarations? **color: black;
padding: 5px;**
3. Which components are considered properties? **color, padding** 

# Learning JS 

Theres 4 types of JavaScript operators: 

1. **Arithmetic** = ( +, -, *, ( )
2. **Assigment** = (=, +=, -=)
3. **Comparison** = (==, ===, >, <)
4. **Logical** = (&&, ||, !)

### NOTE! 
* A **String** is a data type that is a sequence of text enclosed in single quotation marks. 
* A way that we could use a **function** in a real world problem would be for example a shopping website in which the total price of the items in your cart are added automatically so you don't have to do the math each time. 

# Your code: Conditionals

An if statement checks a <u>function</u>
 and if it evaluates to <u>be true</u> then the code block will execute. 

 `else if` is the most common conditional statement in **JS**. This statement checks another condition if the first `if` condition is false. It basically says; if the condition returns true, run code A, else run code B. 

 3 types of comparison operators: 
 1. == (equal)
 2. === (strictly equal)
 3. != (not equal)

 ### NOTE!
 * `&&` (AND) = all conditions must be true 
 * `||` (OR) = at least *one* condition must be true
