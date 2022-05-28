# Read: 07 - Programming with JavaScript

### Control flow

What is *control flow*? 
>It is the order in which the computer executes statements in a script. -- MDN website

If there is a conditional structure like an "if else" statement in Javascript. The *flow* will check if the **if** condition is met first, if it is then the code finishes and move on to the next. If not, it will
go to the **else** condition and execute the next statement. Below is an example of the JS.

```
if (field==empty) {
    promptUser();
} else {
    submitForm();
}
```
### JavaScript Functions and Operators

What is a JavaScript Function?
>A JavaScript function is a block of code designed to perform a particular task.
A JavaScript function is executed when "something" invokes it (calls it). --w3schools website

Below is an example of a JS *function*.

```
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```
What are Operators?  Operators are symbols in Javascript that have special properties or rules that specify how operands are treated.

The Assignment Operators (=, +=, *=, etc) assigns the right operand to the left. For example, x = y means that x is *assigned* the value y and other way around too, but in JS the x = 5 is good but not 5 = y it will be an error.

The Comparison Operators does compare both operands. For example, **==** means **equal to** ( 5 == 5 or '5' as in 5 number and 5 string), and **===** means **equal value equal type** (number cannot equal string like == ).
 





####Cheat Sheet Links

[Functions](https://www.w3schools.com/js/js_functions.asp)

[Operators](https://www.w3schools.com/js/js_operators.asp)
