---
tags: cssi, javascript
level: 1
languages: javascript
---
# Loops
After the Lesson, you'll be able to understand:
+ Concept of iterating through an array
+ How to use a for loop

Now that we are working with arrays, we have variables with multiple pieces of data attached to them. If we want to call methods on each element in the array separately, we can save ourselves a lot of time and code with loops.
# For loops

Let's do something crazy with our bathroom array.
```javascript
> bathroom
> for (i in bathroom) { bathroom[i] = bathroom[i].toUpperCase() }
> bathroom
```
What happened? We combined a lot of tricks and added a new one, the "for" loop. The "for" loop is for taking the same action on a lot of objects.

The "i" is a variable traditionally used in for loops; it's short for "index". Every time the loop is called, it gets a number corresponding to the index of the list.  0, then 1, then 2, .... all the way up to the length of the "colors" variable. This lets the loop access different entries in "colors" until it's done everything. And our trick of modifying a variable value lets us update each color name.

## Activities

Create a list that stores the numbers 3 through 10.  How would you get the first item in the list?  How would you get the second item in the list? How would you perform an operation on every item in the list?

Create a list named people that stores the names of everyone in your row, in all lowercase.  Write a for loop that capitalizes the first letter of everyone's name.  Make sure to print your list afterwards, to prove to yourself that it worked!
