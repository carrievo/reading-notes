# 06: JS Object Literals; The DOM

### Object literals:
- Objects in JavaScript can be compared to objects in real life. It is a series of variables and functions.
- Variables: In an object, are known as properties of the object. 
- Method: Functions that is part of an object.
- Key: Can only have 1. Keys are used to access their corresponding values.
- Value: is always a function. String, number, Boolean, array.

**Creating an object** looks a little something like this..
- you need an object, key, and value.
 
    var hotel = {                           
      name: 'Ritz Carlton',                    
      rooms: 30,
      booked: 20,

      Check availability: function () {         
        return this.rooms - this.booked;
      }
    }

- Hotel is the object, Ritz Carlton, rooms and booked are properties, and the function is the method.

### DOM:
- which stands for Document Object Model.
- This specifies how browsers should create a model of an HTML page and how JS can access and update the contents.
- API (application programming interface): This lets programs and scripts talk to each other. 
- The DOM tree contains **4** main types of node:
    1. Document Node
        - html
        - body
        - div
    2. Element Node
        - h1
        - h2
        - ul 
        - script
        - you can access/update its content using properties such as *textContent* and *innerHTML* or DOM manupulation techniques.
        - this can content multiple text nodes and child elements that are siblings of each other.
    3. Attribute
        - not children of the element that carries them but they are a part of that element (being a part of h1 and script).
    4. Text nodes
        - text nodes cannot have children and no other branches can come off of it. 
        - *refer to Duckett pg187 model for DOM tree illustration.*

- You can select element nodes by their *id* or *class* attributes, by tag name, or using CSS selector syntax.


*Referenced:* 
Duckett, J. (2014). *JavaScript and JQuery: Interactive Front-End Web Development*.