# Local Storage

- HTML5 Storage is based on named **key/value** pairs. 
- Data is stored as *strings*. If you are storing something other than a string, you'll need to coerce it yourself when you retrieve it.
- By default, 5 megabytes is how much storage space each origin gets.
- You are storing strings, not data in its original format.
- We can save the progress locally within the browser.
- **Web SQL Database**
  - formerly known as WebDB
  - You would use SQL by passing a string to the *executeSql* method with statements - 
    - SELECT, UPDATE, INSERT, DELETE.
  - SQL is like a backend database except you're doing it from JavaScript.


*Referenced*
[“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)