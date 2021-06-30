# Day 8: Operators and Loops

### What are loops?
- It's a quick and easy way to do something repeatedly. 
- The condition has to be true and had to be met
- Cool fact - the *for* loop syntax is the same as how you write loops for *any* other language!

**To set a loop**
1. You must declare the variable
2. Set the condition
3. Set what happens to the variable after each iteration

### There are 3 types of loops
1. While loops
2. For loops
3. Do while 

*We'll be using while and for loops for this class*
- **While loop example**: 
let number = 0;
while(number < 10){
  console.log(number);
  number = number + 1;
}
- When you run this, the output will show numbers 1-9
- **For loop example**:
for(let berry = 0; berry < 10; berry++ ){
  console.log("berry" + berry);
}