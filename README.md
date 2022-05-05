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
{name:'Cielo', job:'NYT',language:'JavaScript', age:21}]
```

1. Write a function named `oddJob` that takes an array of objects and returns an array of objects if the job length is an odd number. 
    
    ```jsx
    oddJob(alumni) //returns [
      { name: 'Jarrit', job: 'TPT', language: 'JavaScript', age: 22 },
      { name: 'Enmanuel', job: 'Asana', language: 'JavaScript', age: 21 },
      {
        name: 'Shemar',
        job: 'SquareSpace',
        language: 'JavaScript',
        age: 23
      },
      { name: 'Cielo', job: 'NYT', language: 'JavaScript', age: 21 }
    ]
    ```
2. Write a function named `birthYear` that takes an array of objects and returns an array of objects with a new property called birth year and the value containing the year they were born. You may assume the year is 2022. 
    
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
3. Write a function named `updateLanguage` that takes an array of objects and updates the language value to ES6 if the language is JavaScript, return the entire object. 
    
    ```jsx
    updateLanguage(alumni) // [
      { name: 'Jarrit', job: 'TPT', language: 'ES6', age: 22 },
      { name: 'Stephanie', job: 'JPMorgan', language: 'ES6', age: 21 },
      { name: 'Devonte', job: 'WW', language: 'ES6', age: 23 },
      { name: 'Enmanuel', job: 'Asana', language: 'ES6', age: 21 },
      { name: 'Shemar', job: 'SquareSpace', language: 'ES6', age: 23 },
      { name: 'Cielo', job: 'NYT', language: 'ES6', age: 21 }
    ]
    ```
4. Write a function named `orderedAlumni` that takes an array of objects and sorts the objects by the age of the alumni from oldest to youngest. 
    
    ```jsx
    orderedAlumni(alumni) // returns [
      { name: 'Devonte', job: 'WW', language: 'JavaScript', age: 23 },
      {
        name: 'Shemar',
        job: 'SquareSpace',
        language: 'JavaScript',
        age: 23
      },
      { name: 'Jarrit', job: 'TPT', language: 'JavaScript', age: 22 },
      {
        name: 'Stephanie',
        job: 'JPMorgan',
        language: 'JavaScript',
        age: 21
      },
      { name: 'Enmanuel', job: 'Asana', language: 'JavaScript', age: 21 },
      { name: 'Cielo', job: 'NYT', language: 'JavaScript', age: 21 }
    ]
    ```
5. Write a function named `orderedByJob` that takes an array of objects and sorts the alumni in alphabetical order based on their job property, return an array of the alphabetized job. 
    
    ```jsx
    orderedByJob(alumni) // returns [ 'Asana', 'JPMorgan', 'NYT', 'SquareSpace', 'TPT', 'WW' ]
    ```

6. Write a function named `averageAge` that takes an array of objects and returns the average of all the ages from each age property in each object rounded to the nearest whole number. 
    
    ```jsx
    averageAge(alumni) // 21
    ```
7. Write a function named /`bananaBread` that takes an array of objects and returns an array of the same objects with a new property named bananaBread that has a value of a string using the name and job properties of each object. 
    
    ```jsx
    bananaBread(alumni) // returns [
      {
        name: 'Jarrit',
        job: 'TPT',
        language: 'JavaScript',
        age: 22,
        bananaBread: 'Jarrit got banana bread at TPT'
      },
      {
        name: 'Stephanie',
        job: 'JPMorgan',
        language: 'JavaScript',
        age: 21,
        bananaBread: 'Stephanie got banana bread at JPMorgan'
      }...] 
    ```
 8. Write a function named `ninetiesBabies` that takes an array of objects and returns an array of only the objects where the age property is larger than 21.
    
    ```jsx
    ninetiesBabies(alumni) // returns [
      { name: 'Jarrit', job: 'TPT', language: 'JavaScript', age: 22 },
      { name: 'Devonte', job: 'WW', language: 'JavaScript', age: 23 },
      { name: 'Shemar', job: 'SquareSpace', language: 'JavaScript', age: 23 }
    ]
    ```
9. Write a function named `addSchool` that takes an array of objects and returns a new array where a property of 'school', and value of 'The Marcy Lab School' is added to each object.
    
    ```jsx
    addSchool(alumni) // returns [
      { name: 'Jarrit', job: 'TPT', language: 'JavaScript', age: 22, school: 'The Marcy Lab School'},
      { name: 'Stephanie', job:'JPMorgan', language:'JavaScript', age:21, school: 'The Marcy Lab School'}, 
      { name: 'Devonte', job:'WW', language:'JavaScript', age:23, school: 'The Marcy Lab School'}, 
      ...
    ]
    ```
 10. Write a function named `allUseJavaScript` that takes an array of objects and returns a boolean if for every object, the language property is 'JavaScript'.
    
    ```jsx
    allUseJavaScript(alumni) // returns true
    ```
