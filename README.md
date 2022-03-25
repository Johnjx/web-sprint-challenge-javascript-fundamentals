# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks. 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results. 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

The differences between these array methods is that .map will perform a specified action on each element of the array, .reduce will
attempt to reduce your array to a single value, and .filter will check each element of the array for a value relating to 'truthiness' and discard all other elements not meeting that criteria.

You could use .map to take an array of numbers and multiply each number by a specified amount, returning a new array with the same length and multiplied numbers. You could use .reduce to take an array of objects, with each object containing a population key with a number value, and return a single value that has summed up the population numbers of all of the objects. You could use .filter to take an array of numbers, and check if each number is greater than a specified amount, the result would return a new array with numbers that meet that condition. 

2. Explain the difference between a callback and a higher order function.

A callback is the function that is taken in as the argument for a parameter on a higher order function. 

3. Explain what a closure is.

Closure occurs when a function is created inside of another function. Moreover, this is the act of the inner function reaching outside of its scope to access variables in the lexical environment of its outer function. 

4. Describe the four principles of the 'this' keyword.

The first principle is window binding: When you call 'this' while in the global bounds of your program you will receive the entire window object back. This is because 'this' is not tied to a specific scenario inside of your program. In general, anything defined in the global scope of your program is linked to the window of the program.

The second principle is implicit binding: When using dot notation to call a method, the object to the left of the dot is bound to the call. The 'this' keyword is tied only to the object in this case.

The third principle is new binding: When you are creating an instance of a class, via the reference to a constructor function, you use the 'new' keyword. 'new' tells your program that the context of the 'this' keyword will include the called class.

The fourth principle is explicit binding: When you link different objects together through the use of .call, .bind, or .apply, the context of the 'this' keyword will reference the object being linked. 

5. Why do we need super() in an extended class?

The super keyword finalizes the call to the class being extended. It allows our child class to access the properties and methods of the parent class.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your repo to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/master; your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://bloomtech.notion.site/bloomtech/BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) (see part 2, submitting an assignment with codegrade).
