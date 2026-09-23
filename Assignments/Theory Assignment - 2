1. What is CSS Box Model?

The CSS Box Model describes how every HTML element is represented as a rectangular box. It consists of four parts:
- Content: The actual text, image, or other content.
- Padding: Space between the content and the border.
- Border: A line surrounding the padding and content.
- Margin: Space outside the border between elements.

Example:
.box {
    width: 200px;
    padding: 20px;
    border: 2px solid black;
    margin: 10px;
}


2. What is media query? Explain with a sample code.

A media query is a CSS feature used to apply different styles depending on the device or screen size. It is mainly used to create responsive websites.

Example:
body {
    background-color: white;
}

@media screen and (max-width: 600px) {
    body {
        background-color: lightblue;
    }
}

Here, the background becomes light blue when the screen width is 600px or less.


3. What are the features of Bootstrap?

Major features of Bootstrap are:
- Responsive design.
- Mobile-first approach.
- Predefined CSS classes and components.
- Grid system for creating layouts.
- Ready-made buttons, forms, cards, navbars, alerts, etc.
- JavaScript components such as modals and carousels.
- Cross-browser compatibility.
- Easy and fast web development.
- Utility classes for spacing, colors, alignment, and typography.


4. Write an example of basic grid structure in Bootstrap.

Bootstrap uses a 12-column grid system. A basic grid structure contains a container, row, and columns.

Example:

<div class="container">
    <div class="row">
        <div class="col">Column 1</div>
        <div class="col">Column 2</div>
        <div class="col">Column 3</div>
    </div>
</div>

The three columns automatically share the available width equally.


5. What is CSS Selectors?

CSS selectors are patterns used to select HTML elements that we want to style.

Common types are:
- Element selector: p { color: red; }
- ID selector: #header { color: blue; }
- Class selector: .box { background: yellow; }
- Universal selector: * { margin: 0; }
- Group selector: h1, h2, p { color: green; }
- Attribute selector: input[type="text"] { border: 1px solid black; }


6. What are CSS backgrounds? List the properties.

CSS background properties are used to set the background of an HTML element.

Important background properties are:
- background-color: Sets the background color.
- background-image: Sets a background image.
- background-repeat: Controls whether the image repeats.
- background-position: Sets the position of the background image.
- background-size: Sets the size of the background image.
- background-attachment: Controls whether the background scrolls with the page.
- background: Shorthand property for setting multiple background properties.

Example:
body {
    background-color: black;
    background-image: url("image.jpg");
    background-size: cover;
    background-position: center;
}


7. How can we overlap elements in CSS?

Elements can be overlapped using CSS positioning and the z-index property.

Example:
.box1 {
    position: absolute;
    left: 50px;
    top: 50px;
    z-index: 1;
}

.box2 {
    position: absolute;
    left: 80px;
    top: 80px;
    z-index: 2;
}

The box with the higher z-index appears above the other box.


8. What are the different positioning properties in CSS?

CSS has five main position values:

- static: Default position of an element.
- relative: Positions an element relative to its normal position.
- absolute: Positions an element relative to its nearest positioned ancestor.
- fixed: Keeps an element fixed relative to the browser window.
- sticky: Acts like relative until a specified scroll position is reached, then behaves like fixed.

Example:
.box {
    position: relative;
    top: 20px;
    left: 30px;
}


9. What is ECMAScript?

ECMAScript is a standard specification that defines the core features and syntax of scripting languages such as JavaScript.

JavaScript is an implementation of the ECMAScript standard. ECMAScript defines features such as variables, functions, objects, classes, arrays, loops, and newer language features.


10. What is the difference between var, let and const in JavaScript. Explain Temporal Dead Zone.

var, let, and const are used to declare variables in JavaScript.

var:
- Function-scoped.
- Can be redeclared.
- Can be reassigned.
- Hoisted and initialized with undefined.

let:
- Block-scoped.
- Cannot be redeclared in the same scope.
- Can be reassigned.
- Hoisted but remains in the Temporal Dead Zone until its declaration is reached.

const:
- Block-scoped.
- Cannot be redeclared.
- Cannot be reassigned.
- Hoisted but remains in the Temporal Dead Zone until its declaration is reached.

Example:

var x = 10;
let y = 20;
const z = 30;

Temporal Dead Zone (TDZ):
The Temporal Dead Zone is the period between entering a block and reaching the declaration of a let or const variable. During this period, accessing the variable causes a ReferenceError.

Example:

console.log(a); // ReferenceError
let a = 10;

Here, 'a' exists in the scope but cannot be accessed before its declaration.
