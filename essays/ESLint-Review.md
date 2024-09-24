---
layout: essay
type: essay
title: "How would I Rate ESLint?"
# All dates must be YYYY-MM-DD format!
date: 2024-09-23
published: True
labels:
  - TypeScript
  - ESLint
  - Coding Standards
---

## So, what is ESLint?
<p>
My understanding of ESLint is that it is a code analysis tool which can be used within Integrated Development Environments (IDEs) to help identify and resolve problems in code. It is very useful in maintaining a certain level of code quality by enforcing coding conventions and finding potential errors that could lead to annoying bugs down the line.
</p>

<p>
  Certain interesting aspects of ESLint are that it:
</p>

<ol>
  <li>Is customizable with predefined or custom configurations.</li>
  <li>Automatically detects and highlights certain syntax issues, potential bugs, and problematic patterns in the code.</li>
  <li>Is seamlessly integrated and accessible through plugins for many IDEs</li>
</ol>

## My Experiences Using ESLint
<p>
  For my first experience with the tool, I enabled it on an already exisiting Typescript file that I had written. I was pleasantly surprised with how many red squiggly lines were scattered across the page, highlighting violations to the AirBnB sytyle guide. What was initially puzzling is the fact that the script compiles and runs without any errors. From this, I could categorize the errors I observed into two camps. One, those that only point out how my writing *style* differs from the AirBnB style convention, and two, errors that have the potential to turn into potential bugs. These potential bugs could be triggered, for example, by a user inadvertently selecting an input that wasn't account for in the original script.
</p>

### Types of Errors
<p>
  The first kind of error is less essential for the program's functionality but it is always a best practice to follow the style convention since it helps with organization, consistency, and readability for yourself and other developers. The second type of error is what really developed my understanding of how the script I wrote works. It also trained my ability to spot how my bad writing habits could create potential headaches in the future when trying to resolve bugs in the program. These mistakes would be things related to variable declarations (using let/const/var) and defining variable types such as numbers, strings, and unknowns.
</p>

## Conclusion?
<p>
  So as a result, anything I write post introduction to ESLint has been more consistent and resilient to bugs. I can relate it to how a clean and tidy working environment is often conducive towards higher productivity and quality of work. When you can more easily follow what your code is doing you will be better off when something does inevitably go wrong.
</p>

<p>
  In conclusion, 10/10 would recommend
</p>

