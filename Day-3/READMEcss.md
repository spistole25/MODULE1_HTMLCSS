Forms Homework
        go back to step 49 to understand the label on top of the element selectors

CSS - week2 Notes:
pseudo selectors
    for interactive states, things like hovering. Changing the css
Example:
input:hover{
    background-color: #e0e0e0;
}

CSS Selectors for Form Elements
    use to target specific HTML form elements; 
Examples:
 input,
 textarea,
 select,
 p,
 h1,
 h2
element{
    property: value;
}
input{
    margin: 10px;
    padding: 8px;
}

CSS Classes for Form Styling
    apply classes to form elements
Examples:
html
<input> type="text" class="form-input"
css
.form-input{
    property: value
}

Box model and Margins
    adjust the box model properties to control spacing and layout
Example:
input, textarea, select {
    margin: 10px;
    padding: 8px;
}

Width and Max Width:
    set the width and maximum width for form elements
Example:
input{
    width: 100%;
    max-width: 400px;
}

Text Alignment and Font Styles:
    Align text and customize font styles
Example:
label {
    text-align: right;
    front-weight: bold;
}

Background and Border Styles:
    customize background color and add borders to form elements
Example:
input, textarea{
    background-color: #f0f0f0;
    border: 1px solid #ccc
}

Transitions
    apply smooth transitions for a polished user experience
Example:
input{
    transition: background-color 0.3s ease;
}



COMMON CSS PROPERTIES
Color Properties:
'color': Sets the text color.
'background-color': Sets the background color.
    body {
  color: #333; /* Text color */
  background-color: #fff; /* Background color */
}

Typography:
'font-family': Defines the font family.
'font-size': Sets the font size.
'font-weight': Specifies the font weight.
    h1 {
  font-family: 'Arial', sans-serif;
  font-size: 24px;
  font-weight: bold;
}

Box Model:
'width': Sets the width of an element.
'height': Sets the height of an element.
'margin': Sets the margin outside the border.
'padding': Sets the padding inside the border.
'border': Sets the border properties.
    .box {
  width: 200px;
  height: 150px;
  margin: 10px;
  padding: 20px;
  border: 1px solid #ccc;
}

Layout:
'display': Defines the display behavior (e.g., block, inline, flex).
'position': Specifies the positioning method (e.g., static, relative, absolute).
'float': Places an element on the left or right side of its container.
    .container {
  display: flex;
  position: relative;
  float: left;
}

Text Properties:
'text-align': Sets the horizontal alignment of text.
'line-height': Specifies the height of a line of text.
'text-decoration': Adds decoration to text (e.g., underline, overline).
    p {
  text-align: justify;
  line-height: 1.5;
  text-decoration: underline;
}

Background Properties:
'background-image': Sets the background image.
'background-repeat': Specifies how a background image repeats.
'background-position': Sets the starting position of a background image.
    .hero {
  background-image: url('hero.jpg');
  background-repeat: no-repeat;
  background-position: center center;
}

Transition and Animation:
'transition': Specifies the transition properties.
'animation': Defines the animation properties.
    button {
  transition: background-color 0.3s ease;
}

@keyframes slide {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

COMMON CSS SELECTORS:
span: Selects all <span> elements.
a:hover: Selects all <a> elements on hover.
img: Selects all <img> (image) elements.
button: Selects all <button> elements.
form: Selects all <form> elements.
input[type="text"]: Selects all <input> elements with type="text".
input[type="checkbox"]: Selects all <input> elements with type="checkbox".
input[type="radio"]: Selects all <input> elements with type="radio".
input[type="tel"]: 
textarea: Selects all <textarea> elements.
ul: Selects all unordered list <ul> elements.
ol: Selects all ordered list <ol> elements.
li: Selects all list item <li> elements.
header: Selects all <header> elements.
footer: Selects all <footer> elements.
*: Universal selector (selects all elements).
p: Selects all <p> (paragraph) elements.
h1, h2, h3: Selects all heading elements from <h1> to <h3>.
a: Selects all <a> (anchor) elements.
input: Selects all <input> elements.
ul li: Selects all list items (<li>) within unordered lists (<ul>).
ol li: Selects all list items (<li>) within ordered lists (<ol>).
div: Selects all <div> elements.
#id: Selects an element with a specific ID (e.g., #header).
.class: Selects all elements with a specific class (e.g., .nav-link).
nav: Selects all <nav> elements.
section: Selects all <section> elements.
article: Selects all <article> elements.
aside: Selects all <aside> elements.
main: Selects all <main> elements.
figure: Selects all <figure> elements.
figcaption: Selects all <figcaption> elements.
blockquote: Selects all <blockquote> elements.
q: Selects all <q> (inline quotation) elements.
cite: Selects all <cite> elements.
abbr: Selects all <abbr> (abbreviation) elements.
address: Selects all <address> elements.
time: Selects all <time> elements.
progress: Selects all <progress> elements.
details: Selects all <details> elements.
summary: Selects all <summary> elements.
fieldset: Selects all <fieldset> elements.
legend: Selects all <legend> elements.