# JavaScript Variables

- There are `3` types of variables in JavaScript: ***var***, ***let***, and ***const***.
 
## <ins>Quick Overview</ins>:

   - **let:** If a variable is going to be ***reassigned later*** within the application, this is the ideal variable type to use.
   - **var:** It's better to use either let or const for variables, but this variable type will still work and is still used in applications to this day. This variable can be ***updated and re-declared***.
   - **const:** If the variable will ***never change or won't be reassigned*** anywhere else in the application, this keyword is the best option.

## Good things to remember:

   - The `var` variable is <ins>globally-scoped</ins> and can be <ins>updated</ins> and <ins>re-declared</ins>.
   - The `let` variable is <ins>block-scoped</ins> and can be updated but <ins>not re-declared</ins>.
   - The `const` variable is <ins>block-scoped</ins> and cannot be <ins>updated</ins> or <ins>re-declared</ins>.

#

1. **<ins>Global Scope</ins>:** A variable declared ***outside*** a **function**. This means all scripts and functions on a web application or webpage can access this variable.

2. **<ins>Block Scope</ins>:** A variable declared ***inside*** a **block**. This means we can use these variables inside of loops, if statements, or other declarations within ***curly*** brackets and have them be only used for that declaration instead of the entire application having access to it.

## [Examples](https://github.com/ShubhamJagtap2000/JavaScript-Basics/tree/main/01%20Variables/Examples):

```
var variableOne = 'Linus Torvalds';

let variableTwo = 50;

const variableThree = 'Creator of the Linux Kernel';
```

- Variables are very easy to use and understand in JavaScript, they can store a lot of information with very little code.

|Data Type|	Example|
|--|-- |
|Number	|200|
|String	|'Neo'|
|Boolean|	True or False|



