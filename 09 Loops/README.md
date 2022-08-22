# JavaScript Loops

- Loops can be complicated, there are `for` loops, `while` loops, and `do...while` loops. 

# for Loop

- We will be creating a few mini-projects that will loop through a set of numbers.

- Here is how a for loop structure looks like:
```
for(component 1, component 2, component 3)
{
  //code;
}
```

- Let's break [this](https://github.com/ShubhamJagtap2000/JavaScript-Basics/blob/main/09%20Loops/Examples/for-loop.js) code down line by line:
```
for (a = 1; a <= 10; a++) 
{
    console.log(`Number: ${a}`); // Outputs 1-10 in our console
}
```

- This code takes `a`, our variable, and loops through our specified range `1-10` and ***prints*** this to the console. 

- By running this loop, we save our counter, or our range of numbers, to the variable `a`.

- You'll notice that we have `three` statements (or components). Here is a quick list of what each one does:

    - The **first** component `a = 1`: Executes ***before*** the loop starts
    - The **second** component `a <= 10`: Defines the ***condition*** for our loop
    - The **third** component `a++`: Executes each time ***after*** the loop starts

- **IMPORTANT:** Each statement **must** be separated by a ***semi-colon***. We can have more than one value within our first statement, but they **must** be separated by ***commas***: 
```
for (a = 1, b = 2; component 2; component 3) 
{
  //code
}
```
#

# while Loop

- The while loop is similar to the for loop, with a few minor differences:
```
let x = 0;

while (x <= 3) {

console.log(x++); // Prints 0-3

}
```

- [This](https://github.com/ShubhamJagtap2000/JavaScript-Basics/blob/main/09%20Loops/Examples/while-loop.js) code will loop through `x` as long as it is less than or equal to `3`. 

- This loop will ***continuing*** running until the desired outcome is met. 
- Loops can be dangerous if the syntax is incorrectly written, then you can easily start an infinite loop, which isn't good for anyone in most cases. To avoid this, make sure that the loop eventually becomes ***false***.

#

# do...while Loop

- The basics of the do...while loop is the code will execute the loop ***before checking*** if the condition is `true`.

[Example](https://github.com/ShubhamJagtap2000/JavaScript-Basics/blob/main/09%20Loops/Examples/do-while-loop.js):
```
let c = 10;

do {

console.log(c++); // Outputs 10-50

} 
while (c <= 50);
```

- This code will `ALWAYS` execute ***at least once***. 

- It does this because loops normally require the conditions to be true, but a do...while loop doesn't require this as it executes ***before*** checking if the condition is truthy.

