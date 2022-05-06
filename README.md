# Code Challenge: Control Flow

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
{name:'Jarrit', job:'TPT',language:'JavaScript', age:22}, 
{name:'Stephanie', job:'JPMorgan',language:'JavaScript', age:21}, 
{name:'Devonte', job:'WW',language:'JavaScript', age:23}, 
{name:'Enmanuel', job:'Asana',language:'JavaScript', age:21},
{name:'Shemar', job:'SquareSpace',language:'JavaScript', age:23},
{name:'Cielo', job:'NYT',language:'JavaScript', age:21},
{name:'Carmen', job:'Marcy Lab School',language:'JavaScript', age:21},
{name:'Itzel', job:'Marcy Lab School',language:'JavaScript', age:22},
{name:'Ray', job:'Square Space',language:'JavaScript', age:20},
{name:'Jan', job:'Square Space',language:'JavaScript', age:22},
{name:'Uzma', job:'Time Share',language:'JavaScript', age:22}]
```


1. Write a function named `birthYear` that takes an array of objects and returns an array of objects with a new property called birth year and the value containing the year they were born. You may assume the year is 2022. 
    
    ```jsx
    birthYear(alumni) // returns [
      {
        name: 'Cielo',
        job: 'NYT',
        language: 'JavaScript',
        age: 22,
        birthYear: 2001
      }...
    ]
    ```
---
**Bonus Questions**

2. Write a function named `updateLanguage` that takes an array of objects and updates the language value to ES6 if the language is JavaScript, return the entire object. 
    
    ```jsx
    updateLanguage(alumni) // [
      { name: 'Jarrit', job: 'TPT', language: 'ES6', age: 22 },
      { name: 'Stephanie', job: 'JPMorgan', language: 'ES6', age: 21 },
      { name: 'Devonte', job: 'WW', language: 'ES6', age: 23 },
      { name: 'Enmanuel', job: 'Asana', language: 'ES6', age: 21 },
      { name: 'Shemar', job: 'SquareSpace', language: 'ES6', age: 23 },
      { name: 'Cielo', job: 'NYT', language: 'ES6', age: 21 }
      ...
    ]
    ```


3. Write a function named `addSchool` that takes an array of objects and returns a new array where a property of 'school', and value of 'The Marcy Lab School' is added to each object.
    
    ```jsx
    addSchool(alumni) // returns [
      { name: 'Jarrit', job: 'TPT', language: 'JavaScript', age: 22, school: 'The Marcy Lab School'},
      { name: 'Stephanie', job:'JPMorgan', language:'JavaScript', age:21, school: 'The Marcy Lab School'}, 
      { name: 'Devonte', job:'WW', language:'JavaScript', age:23, school: 'The Marcy Lab School'}, 
      ...
    ]
    ```
