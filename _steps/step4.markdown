---
layout: step
number: 4
part: 1
title: Functions
permalink: step4/

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
A function is like a blueprint, an action that you want to do.
It takes some input variables called arguments, does some manipulation on
it and returns the output. Use the keyword 'return' to define the return value.
To create a function use the following format:

```javascript
function functionName(argument) {
    return argument * 2;
};
```

This function will take one argument and return the argument multiplied by 2.
Our function won't actually run unless we 'call' it.
To 'call' the function we write:
```javascript
functionName(10);
```

Now we will call our function with argument that is 10. And our function
will return us 20. To see what our function returns us we can console.log
it, for example:
```javascript
console.log(functionName(10));
```

----

#### TASKS TO DO
1. Create a function to add multiple numbers. 
 * STEP 1 : Name it 'add' and pass in two arguments (num1 and num2). To pass multiple arguments into function we separate them with a comma.
 * STEP 2 : This function should return us a sum of num1 and num2.
 * STEP 3 : Call the function passing numbers 2 and 3 as arguments.
 * STEP 4 : Log the result to see it. (Console.log())
2. Create a function to subtrack numbers from each other. 
 * STEP 1 : Name it 'subtrack' and pass in two arguments (num1 and num2)
 * STEP 2 : This function should return us a subtraction of num1 and num2.
 * STEP 3 : Call the function passing numbers 5 and 1 as arguments.
 * STEP 4 : Log the result to see it. (Console.log())
3. Instead of numbers to pass as arguments, create variables that store
those numbers and pass them as an arguments to your function. Call your function and Log your result.