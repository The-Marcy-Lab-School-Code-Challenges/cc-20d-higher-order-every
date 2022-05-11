# Code Challenge: Higher Order Fluency

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

**All the following problems can be solved using a higher order array method. You cannot use .forEach() to solve the following problems.** 

**Test all your solutions for the questions with the following variable:** 

```jsx
const alumni = [
{name:'Jarrit', job:'TPT',language:'JavaScript', age:20}, 
{name:'Stephanie', job:'JPMorgan',language:'JavaScript', age:24}, 
{name:'Devonte', job:'WW',language:'JavaScript', age:23}, 
{name:'Enmanuel', job:'Asana',language:'JavaScript', age:23},
{name:'Shemar', job:'SquareSpace',language:'JavaScript', age:23},
{name:'Cielo', job:'NYT',language:'JavaScript', age:19},
{name:'Carmen', job:'Marcy Lab School',language:'JavaScript', age:21},
{name:'Itzel', job:'Marcy Lab School',language:'JavaScript', age:22},
{name:'Ray', job:'Square Space',language:'JavaScript', age:21},
{name:'Jan', job:'Square Space',language:'JavaScript', age:18},
{name:'Uzma', job:'Time Share',language:'JavaScript', age:22}]
```

1. Write a function named allUseJavaScript that takes an array of objects and returns a boolean if for every object, the language property is 'JavaScript'.
    
    ```jsx
    allUseJavaScript(alumni) // returns true
    ```
---
**Bonus Question**

2. Write a function named `oldEnough` that takes an array of objects and returns a boolean if for every object, the age is greater than 20.
    
    ```jsx
    oldEnough(alumni) // returns false
    ```
