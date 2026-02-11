# HTML Links, JS Functions, and Intro to CSS Layout

## Creating Hyperlinks 

A basic link in HTML is created by wrapping text or other content inside an `<a>` element and using the `href` attribute. The previously mentioned attribute is known as a *Hypertext Reference* and it contains the URL or link for an `<a>` tag. 
There are ways to ensure that our links are readable to all who visit our sites. One of them is avoiding vague text and describing specifically what the link does. Also, ensuring theres enough readable contrast between colors and the background. You can verify your accesibility by using screen reader tests. 

## CSS Layout 

 Elements on a webpage layout in **Normal Flow** if you *haven't* applied any CSS to change the way they behave. 

 |Block Level | Inline |
 |------------|--------|
 | They always start in a new line | They floe along the same line |
 | Have width, height, margin and padding | Cant have width or height applied |
 | They take up the full width | They only take up necessary width

 * <u>Static</u> positioning is the default for every html element.

 |Absolute Positioning | Fixed Positioning | 
 |---------------------|-------------------|
 | Positioned relative to the document body | Stays in place even when you scroll the page |
 | Element positioning is relative to it's nearest ancestor | Element positioning relstive to the viewport | 
 | Element scrolls with page | Used for navigation bars, floating buttons or headers 

 ### <u>Advantages of using Absolute Positioning:</u>

With absolute positioning we can create isolated UI features that don't interfere with the layout or other elements of the page. When positioning elements, you don't have to position elements based on relative position within the normal flow but rather it specifies the distance the element should be from each of the containing elements sides. 

## Functions and Reusable Blocks of Code 

**Invoking Functions:**

- Invoking a function is done by including the function's name in the code followed by a parenthesis. Is important to note that when you *invoke* a function you are *running* it or *calling* the function. 

**Declaring Functions:**

- Declaring a function is done when you define a function and tell **JS** what it does. In this case, you are just creating the function for later use but not running it. 

| Parameters | Arguments | 
|------------|-----------|
| Values that need to be included inside the function's parenthesis. Parameters are optional and you don't have to specify them. It acts as a place holder for the value the function will receive when invoked. | Values that are passed into the parameters function when you invoke it. It fills the parameter's place and is used inside the function. | 

## Pair Programming

Pair programming is a great learning strategy to keep improving your coding skills. In my experience being able to catch mistakes and figuring out how to fix these mistakes teaches me the most! When it comes to pair programming though, having a partner as another set of eyes might help you speed up the process of finding errors. This also helps you learn since you and your partner are constantl councing off ideas and sharing information. Collaborating may help make coding less stressfull since you don't have to struggle alone on issues and you can learn faster. 
