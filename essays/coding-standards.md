---
layout: essay
type: essay
title: Making Coding Standards Stick
# All dates must be YYYY-MM-DD format!
date: 2020-02-13
labels:
  - eslint
  - javascript
---
## Introduction
<img class="ui small right floated image" src="../images/eslint.png">
ESLint is a tool for Javascript which detects deviations from coding standards. We have been using it in my software engineering class as a plugin for IntelliJ, an IDE for Javascript. Using ESLint with IntelliJ, although frustrating at first, is becoming a fast way to cement my Javascript skills by teaching me to use best practice coding standards.

I mentioned in a previous essay (Unlikely Origins) that I started coding (for the most part) on Myspace and pet sites. This means that I was coding HTML and CSS in a small textbox which I had to constantly update to check my progress. If something was wrong with what I had written, I wouldn't figure it out until I reloaded the target page and found the whole layout ruined.

Using ESLint with IntelliJ solves this kind of problem. One of the major advantages of a syntax/coding standard checker like ESLint is that it ensures that your code can run. It will alert you if you are missing a brace or a semicolon somewhere.

However, ESLint has other (and perhaps greater) advantages. It ensures that you adhere to proper coding standards, which means proper spacing, indentation, variable types, and more. Although this may seem unnecessary at first (why change your spacing and indentation if your code runs fine?) it has numerous advantages. The most major advantages, in my opinion, are improving your code's readability and efficiency.

## Readability
<img class="ui small left floated image" src="../images/readability.jpg">
ESLint ensures my code (and that of anyone else using it) is universally readable and adheres to a coding standard. This is imperative if I ask someone else to debug my code. Everyone has a different coding style, but that means it is more difficult for one person to read another person's code, and therefore things like collaboration and debugging take longer than they should. ESLint will take two different coding styles and ensure that they are mutually readable; they will have the same spacing and indentation so there is no ambiguity. While it might seem obvious that handing someone an "unreadable" piece of code to debug is rude, "unreadable" is subjective. ESLint takes away the subjectivity and makes sure all code is readable. Thus, once I learn the coding standard of ESLint, if someone else using ESLint asks me to debug their code, I don't have to stress about navigating a code with confusing spacing.

## Efficiency
ESLint also ensures that I learn how to write better, more efficient code. My ICS 314 class requires that my code passes all ESLint error checking and that I get a green checkmark before I turn in coding assignments, and this is an efficient way to correct any errors I may accidentally make and prevent me from making them over and over again. For example, if I use "let" to create a variable and don't change that variable in my code, ESLint will alert me that I have to use "const" instead. Thus, while "let" would run, using "const" is better practice, and ESLint teaches me by correction not to make the same mistake. It won't take me more than 3 or so times of making the "let"/"const" error until I remember that ESLint will give me an error for it. It's an effective method of nipping coding mistakes in the bud and ensuring people will continue to use best practice methods of coding.

While that green checkmark in ESLint is frustrating at first, I've learned to appreciate it. It is an effective way to use habit to prevent common coding errors and provides suggested solutions for many errors. It also ensures that I write readable code. The habits of readability and best practice coding are things that will stay with me even after I exit the program, which make ESLint an excellent tool for learning a new coding language.