# Day 7: Programing with JavaScript

### Functions:
- A function is basically the **action**.
- This allows you to write code in larger, more logical chunks and focuses on what X does, rather than how X does it.
- For it to qualify as a function, there is an input and return output with a relationship, you then must define it somehwer eint he scope from which you wish to call it.

example:
function fNamelName(){
  let fName = prompt('what is your first name?');
  let lName = prompt('what is your last name?');
  return  fName + ' ' + lName ;
}
console.log(fNamelName());

Note: Function can also look like..
var fNamelName = function(){
