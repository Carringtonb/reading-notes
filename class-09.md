# HTML and CSS

### Chapter 7: Forms
* Form can refer to different elements that allow you to collect information from visitors to your site. IE **Google Search Bar**
* A user inputs information, the server processes that information and returns a new page based on the users input.
    * To differentiate between various pieces of inputted data, information is sent from the browser to the server using name/value pairs.
* Every `<form>` element requires an action attribute. Forms can also be sent using one of two methods; *get* or *post* IE `<form action="http://www.example.com/example." method="get">`
* The `<input>` element is used to create several different form controls.
    * type='text' - creates a single line of text input
    * name="username" - stores the input of the users username
    * maxlength - sets a parameter for maximum number of characters allowed for input
    * type="password" - creates a text box but every character entered are blocked out
   *  `<textarea>` - creates a multi line text input box.
### Chapter 14: Lists, Tables, and Forms
*  list-style-type allows you to control the shape or style of a bullet point
    * You can specify an image to act as a bullet point using the list-style-image property
* Tables have many properties that can be adjusted
    * width
    * padding
    * text-transform
    * letter-spacing, font-size
    * border-top, border-bottom
    * text-align
    * background-color
    * :hover
* Forms are easier to use if the form controls are vertically alligned using CSS
* Forms benefit from styles that make them feel more interactive.


# JavaScript and JQUERY

### Chapter 6: Events
* HTML elements nest inside other elements. If you hover or click on a link, you will also be hovering or clicking on its parent elements.
* The flow of events only really matters when your code has event handlers on an element and one of its ancestor or descendant elements.
* The event object can tell you where the cursor was positioned when an event was triggered.
* When an event occurs on an element, it can trigger a JavaScript function.
* You can use event delegation to monitor for events that happen on all of the children of an element.
* The most common used events are W3C DOM events.