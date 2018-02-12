---
layout: step
number: 5
part: 1
title: Conditional Statements
permalink: step5/

keywords:
  - term: package.json
    define: A `package.json` is the file used to store information about a Node.js project, such as its name and its dependencies. Read more [here](https://docs.npmjs.com/files/package.json).

  - term: dependencies
    define: Dependencies are external code packages that are required to run your project.

  - term: npm
    define: npm is a "package manager" for Node.js, meaning it allows you to easily install external packages (or chunks of code) published by others and use them in your project.

  - term: npm init
    define: The command used to create a new `package.json` file.  By default it will prompt the user for information, but using the `-y` flag will cause it to use the default values for each.

---
#### CONDITIONAL STATEMENT

##### IF - ELSE STATEMENT

What if we want our program to make a decision about which function it
should run? In this case we can use conditions.
If you have a TV you can watch it in the evening. If not, you might do
something else.  It's the same with code. You can give an 'if' condition to a machine to
make a decision about what part of the code to run.
Structure:

```javascript
if (condition) {
    do this
} else {
    do something else
}
```
Example:

```javascript
var number = 7;
if (number > 7) {
    console.log('Our number is bigger than 7');
} else {
    console.log('Our number is smaller than 7');
}
```

##### IF - ELSE IF - ELSE
Hmm, but what if we have 4 arithmetical operations in our calculator? Well,
    we can use an if - else if - else structure.
    Example;

```javascript
    var number = 7;
    if (number > 7) {
        console.log('Our number is bigger then 7');
    } else if (number < 7) {
        console.log('Our number is smaller then 7');
    } else {
        console.log('Our number is equal to 7');
    }    
```

----

#### TASKS TO DO 

1. We have 2 functions from the previous task - add and subtract.
Let's tell the machine to decide what action to run depending on the arithmetical
operator(+,-,/, * etc). If the operator is '+', we should use the add function, else we should use the subtract function.
 * STEP 1 : Create a variable called operator and let it be equal to '-'.
 * STEP 2 : Create an if/else statement based on what operator we have. If we have an operator equal to '+', we call add function with any two numbers,
else the subtract function with any 2 numbers.
 * STEP 3 : Log your result. (Console.log())

 2. Create 2 more functions and name them divide and multiply. After
that let's extend our 'if else' check that we already created by checking if
it is equal to '/' - call 'divide' function, if it is '*' call multiply
function, else console.log - "Sorry, we don't know this operator".