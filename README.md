# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each.

    -map reduce and filter will all loop over each item in an array
    -map requires one parameter and a return. It will return an array full of new items you specify. You can use map to extract values from an array, or even to just call a function on every item in an array.
    -reduce requires two parameters. It will return one specific item/value, specified by you. I look at it as a science expiriment, adding a bunch of ingredients just for one little drop at the end. You can use reduce for countless tasks, but a few good use cases for reduce is getting the maximum value, sum, or average from a group of numbers inside your data.
    -filter requires one parameter and doesn't require a return. With filter, you're essentialy writing a conditional statement, where everything that is true (or false, depending on your conditional) will be passed into a new array. Filter is great for when you want to extract a certain type of data from an existing data set. For example: If you wanted to filter out all the users above the age of 21. Filter is also great for filtering repeated out of an array.

2. Explain the difference between a callback and a higher order function.
    
    -a callback function is a function that you pass into other functions as an argument. A higher order function is a function that accepts functions as an argument, or returns a function.

3. Explain what a closure is.

    -closure is when an inner function reaches out of its scope, to an outer function's scope, to grab a value that isn't inside the function itself. A function inside of a function represents closure.

4. Describe the four principles of the 'this' keyword.

    -Window: 'this' is binded to window by default, global object in node, or returns undefined in strict mode. 
    -Implicit: 'this' is binded to whatever is left of the dot
    -Explicit: 'this' is binded to what you specify after .call .bind or .apply
    -New: 'this' is binded to the object you will be creating when you call the constructor function.

5. Why do we need super() in an extended class?

    -We use super() in a child class to allow that child access to the properties and methods from a parent class.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

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
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

