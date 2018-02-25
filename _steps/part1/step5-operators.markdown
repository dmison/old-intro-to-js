---
layout: step
number: 5
part: 1
title: Operators
permalink: step5/

#keywords:
#  - term:
#    define:

---

All programming languages have constructs called *operators*. An operator is a character that represents an action, or sometimes a relationship. An operator affects whatever is in front of it in a particular way, according to the kind of operator it is, and according to whatever comes after it.

You're already familiar with operators from when you learned maths: `+` is an operator that represents the action of *addition*. When we use `+` in maths, we take whatever is in front of the `+` and add whatever comes after the `+` to it.

Operators in programming work the same way. There are lots of operators for doing maths, called *arithmetical* operators. But there are also operators for concepts in logic, like *and* and *or*, and for many other things. The dot `.` and the parentheses `()` in `console.log()` are operators, too, but these are a little more complicated.

We're going to start with *arithmetical* operators, since you already understand how most of them work in the real world.

#### ARITHMETICAL OPERATORS
JavaScript includes several standard arithmetical operators (`+`, `-`, `/`, `*`) that you can use to do maths with your numbers.

```javascript
var sumOfNumbers = 1 + 3;
alert(sumOfNumbers);
```

This will pop-up an alert box with the number 4.

TIP: Note how we didn't put 1 and 3 in quotes, because they are numbers.

#### COMPARISON OPERATORS

JavaScript's Comparison operators are used
to compare values (>, <, <=, =>, ==, !=). Most of them you know from math
classes in school, some of them can be new for you, so '==' is checking
equality, if two values are equal.
'!=' - Checks if they are not equal.

Alert : Don't mix up '=' and '==' as they have different meanings.

----

#### TASKS TO DO
1. Create 3 variables:
 * 1st variable named ten with value 10 inside
 * 2nd variable named three with value 3
 * 3rd variable named multipleOfNumbers that will be equal to 1st variable multiplied by the 2nd variable.
2. As a result, display the value of multipleOfNumbers.
