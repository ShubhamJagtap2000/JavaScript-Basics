# JavaScript Switch Cases

- If you need to test ***multiple conditions***, then most of the time switch cases are best for optimization and readability within your code. 

- If, else if, else statements and switch cases can both do similar tasks, but switch cases are better for ***performing multiple different conditions***. 
- Here's how a [switch case code](https://github.com/ShubhamJagtap2000/JavaScript-Basics/blob/main/05%20Switch%20Cases/Examples/switch-case.js) looks:

```
const animal = 3;

switch (animal) {

case 1:

document.write('Cow');

break;

case 2:

document.write('Chicken');

break;

case 3:

document.write('Monkey');

break;

default:

document.write('Animal?');

} // Outputs Monkey
```

- We use each case to define a number, have our variable hold the number we're pulling from, and the break keyword is used for ending that specific case or switch block. 

- The default keyword is there just in case our variable is equal to something that isn't present in our switch...case code.
