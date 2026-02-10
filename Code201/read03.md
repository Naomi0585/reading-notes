# HTML Lists, Control flow with JS, snd the CSS Box Model

## On this section we will be learning a bit more about HTML, starting with the types of lists you can create. 


| Unordered List | Ordered List |
| -------------- | ------------ |
| `<ul>`         | `<ol>`       |
| Order doesn't matter | Items must be followed in sequence, numbered or ranked.


An **Unordored List** would be ideal If you are looking to make a list where the order of the items is meaningless yet they are still grouped together in no particular order and using the `<ul>` element.

For your convenience you may change the bullet style of these type of lists. Within the bullet shapes are squares, circles or dots. To change the styles, you would use CSS since the bullet style would not be defined in the HTML description of the page. In this case you would be using the *list-style-type* property. 

In an **Ordered List** there are 2 ways to change the numbers on the items; 

1. By using the HTML type attribute and using common type values like letters, numbers, or roman numerals. 
2. Using the *start* attribute on HTML to change what will be the starting number on the list. 


## In CSS there is often a box around things, on this next section we will understand how these boxes work. 

Think of the **Box Model** as a house. There are two people in this house with different personalities. One of these people is *Padding* and they like being inside of the house. Then theres *Margin* and they like being outside. 

### Parts of the Box Model 

* **Content box:** The area where your content is displayed; size it using properties like `width` and `height`.
* **Padding box:** The padding sits around the content as white space; size it using `padding` and related properties.
* **Border box:** The border box wraps the content and any `padding`; size it using `border` and related properties.
* **Margin box:** The `margin` is the outermost layer, wrapping the `content`, `padding`, and `border` as whitespace between this box and other elements; size it using `margin` and related properties.

## Finally, on this section we will learn how JS works in your code.

### Arrays, Operators, Expressions, Conditionals and Loops. 

An **Array** is a way of storing a list of data items under a single variable name. You can store single objects that contain multiple values and we can access each value inside the list individually. 

### Example: 
 `const people = [['pete', 32, 'librarian', ||null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`

 * An array's validity depends on how it's written. For starters, the array needs to be inside square brackets and the values should be separated with commas. The previous example would be valid in **JS** since the array is nested correctly. 

 ## Shorthand Operators

 | Function | Shorthand Operator |
 |----------|--------------------|
 | Addition | `x += f()`         |
 | Left shift | `x <<= f()`      |
 | Exponentation | `x **= f()`   |
 | Logical **AND** | `x &&= f()` |
 | Bitwise **XOR** | `x ^= f()`  |

 ## Expressions 

 `let a = 10;
 let b = 'dog';
 let c = false;`

 How would you evaluate this:
 `(a + c) + b;` 
  
  The answer would be `10dog` because `a + c` -> `10 + false` -> `10 + 0` -> `10` 
  
  * In **JS** when you add a number to a string the number is converted into the string. 

## Conditionals 

In the real word, a great example to understand a *conditional statement* in **JS** would be any website that requires a username and password to access it. The website would need it's program to decide between 2 outcomes in order to grant or restict access. 

## Loops 

An example from personal experience I have for a *loop* is the guessing game we had to create for our About me page assigment. In my case I had some of the questions allow 3 attempts to guess the answer and for this function to run efficently I used a loop, otherwise I would have to write each prompt for the questions 3 times. 