# Forms and Events 

Web Forms are one of the main points of interactions between the user and the website. **Forms** allow users to enter data to immediately update the interface in some way. For web development, forms **Forms** are crucial! 

When creating a *Web Form* from a user's experience point of view, It's important to remember that the bigger your from, the more you risk losing users out of frustration. That's why it is best to keep it simple and use only the data you absolutely need. 

## Form Elements:

1. `<label>` - Improves acessibility when it comes to screen readers and ensures users understand the purpose of each input. 

2. `<button>` - Enables interaction by sending or processing the collected data. 

3. `<input>` - Captures all types of basic user input. 

4. `<select>` - Standarizes input, reduces errors and improves user experience when selecting from limited choices. 

5. `<textarea>` - Provides flexibility for users to enter detailed information beyond *single-line* text. 

## Intro to Events 

Events are things that happen in the system you are programming, which the system tells you about so your code can react to them.
In more simple terms, an event lets a website listen and respond to what users do or what happens on the page. 

The HTML `<button>` element will fire a click event when the user clicks it. We call the `addEventListener()` method on it to add an event listener; this takes two parameters:

* The string "click", to indicate that we want to listen to the click event. Buttons can fire lots of other events, such as "mouseover" when the user moves their mouse over the button, or "keydown" when the user presses a key and the button is focused.
* A function to call when the event happens. In our case, the defined anonymous function generates a random RGB color and sets the background-color of the page <body> to that color.

### Event Objects 

Sometimes, inside an event handler function, you'll see a parameter specified with a name such as `event`, `evt`, or `e`. This is called the event object, and it is automatically passed to event handlers to provide extra features and information.
 The `target` property within an *event object* is useful because it tells you exactly which element triggered the event, no matter where the event listener is attached. This is crucial for making dynamic and efficient interactions.

 ### Bubbling vs. Capturing 

 Event **bubbling** and **capturing** describe the order in which events travel through the DOM (Document Object Model) when an event occurs on a nested element.
 **Capturing** is like a scanner that notices actions before they happen, while **Bubbling** is the chain reaction after the action happens and is recorded. 