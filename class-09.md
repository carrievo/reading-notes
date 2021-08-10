# Read 09: Forms & JS Events

### Forms:
- This is made to collect information. It works when a user fills in a form, presses a button and submits the information to the server. 
- Different form controls:
  - Adding text: where you can input text in a single line/tex box, or you can even mask the characters like how most sites mask password input.
  - Making choices: There you can select 1 or multiple choices with radio buttons, checkboxes or drop-down boxes.
  - Submitting forms: You can submit data like a subscribe button or upload files by uploading. 
- <\form>: to collect information from the user, you need a form which lives inside a form element.
- Information from a form is sent in a name/value pairs.
-HTML5 introduces new form elements which make it easier for users to fill in forms.

### Lists, Tables & Forms:

**Table**: represents information in a grid format and allows us to understand and reference data by referencing information on two axes.
- With the help of **CSS**, you can manipulate the width, spacing, border and background of the table/columns/rows.
*Refer to Duckett pg 132-140 for table examples.*

**Lists**: List markers can be given different appearances by using list-style-type and list-style image properties.
- You can also change the style of the markers to disc, circle, square, etc. 

**Forms**: Forms are more successful if the form controls are vertically aligned using CSS and benefit from styles that make them feel more interactive.

*Referenced:* 
Duckett, J. (2011). *Extra Markup, HTML & CSS: Design and Build Websites*. (pg144-175, pg330-357)

### Events:
- Events are the browser's way of indicating when something has happened. 
  - ex: when a page finished loading or a button has been clicked.
- **Binding**: Process of stating which event you are waiting to happen and which element you are waiting for that event to happen upon.
- How this works is.. 
  1. When an event occurs on an element
  2. It will trigger a JS function.
  3. When the function changes something on the webpage
  4. It feels inactive because it has responded to the user.

- Event delegation: Monitors events that happen on all of the children of an element.
- Most common events used are **W3C DOM**.

*Referenced:* 
Duckett, J. (2014). *JavaScript and JQuery: Interactive Front-End Web Development*. (pg243-292)