# Read 10: Debugging

### Error Handling & Debugging: 

- Debugging is the process of finding errors. 

- JavaScript processes and interprets one line of code at a time. When a statement needs data from another function, it stacks the new function on top of the current task (Duckett pg454).
  - ex:
    1.  function greetUser() {
        return 'hello ' + getName();
      }
    2.  function getName() {
        let name = 'Carrie';
        return name;
      }
    3. let greeting = greetUser();
        alert(greeting);
    4. You should get back, 'Hello Carrie'

- **JS have 7 types of errors**:
    1. SyntaxError: Simple typo.
    2. EvalError: Incorrect use of function.
    3. URIError: Incorrect use of characters (ex: / ? & : ;).
    4. ReferenceError: Variable does not exist or had not been declared yet.
    5. TypeError: Trying to use an object or method that does not exist.
    6. RangeError: Using number outside of its range.
    7. Error: Generic error object in template or prototype.
  - Note: NAN is not an error, you may end up with a value of NAN if you try to perform a mathmatical operation using a value that is not a number. 

- The most useful tool for finding errors is in the **browsers console**. this helps narrow down the area/line the error is located. 
  - Right click and select 'Inspect', and select 'Console'. If there are errors, it will show up in red.

- console.log to check the data. This will be displayed to the user from inspecting the browser.
  - Note: This should be taken out of the code when the site goes live.

*Referenced:* 
Duckett, J. (2014). *JavaScript and JQuery: Interactive Front-End Web Development*. (pg449-486)