---
layout: step
number: 2
part: 1
title: Variables and Data Types
permalink: step2/

keywords:
  - term: package.json
    define: A `package.json` is the file used to store information about a Node.js project, such as its name and its dependencies. Read more [here](https://docs.npmjs.com/files/package.json).

---

#### VARIABLES

A variable is a place to store information. To create (also called declare) a
variable use the keyword 'var', as follows:

```javascript
var variableName;
```
So, we created a variable named variableName, but it has no information or
value inside. It is empty. To give our variable a value (initialize it)
use the '=' sign:

```javascript
variableName = 'Hello world!';
```

We also can create and give value to a variable in one step, as follows:

```javascript
var newVariable = 1;
```
#### DATA STRUCTURES AND TYPES

As you can notice, we can give different types of values to our variables. 

| DATA TYPE        | DESCRIPTION        |
| -----------------|--------------------|
| **String**       |A sequence of characters that represent a text value. For example:  "Hello World!"|
| **Number**       |An integer or floating point number. For example: 42 or 3.14159. Not wrapped in quotes |
| **Boolean**      |true or false|
| **null**         | A special keyword denoting a null value.  |
| **undefined**    |A top-level property whose value is not defined. |
| **Symbol**       |A data type whose instances are unique and immutable. | 
| **Object**       |some description |



You also can use your variables to represent information that they have inside.

```javascript
var hello = 'Hello World';
alert(hello);
```

This will pop-up an alert box with the string 'Hello World!'

----
#### TASKS TO DO

1. Create two empty variables named numberOne and numberTwo
2. Create 2 variables, 1 with your name and the 2nd with your age and display them with an alert pop-up box.