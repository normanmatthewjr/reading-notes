# Read: 08 - Operators and Loops

What are Operators?  Operators are symbols in Javascript that have special properties or rules that specify how operands are treated.

The Assignment Operators (=, +=, *=, etc) assigns the right operand to the left. For example, x = y means that x is *assigned* the value y and other way around too, but in JS the x = 5 is good but not 5 = y it will be an error.

The Comparison Operators does compare both operands. For example, **==** means **equal to** ( 5 == 5 or '5' as in 5 number and 5 string), and **===** means **equal value equal type** (number cannot equal string like == ).

### Loops and Iterations

Loops are an easy way for you to do something repeatedly. **For Statement** it repeats until a specified condition is false.
```
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
```
Below is an example of a *For* loop.

```
let str = '';

for (let i = 0; i < 9; i++) {
  str = str + i;
}

console.log(str);
```

**While Statement** repeats the code until a specified condition is true. Below is an example of a *while* loop.

```
let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}
```
