# CSC 141, Homework 2, Fall 2026

# HW 2: Decorations

## Overview

This homework follows similar to HW1, but with some notable differences. This homework also:

  1. incorporates functions
  2. permits AI (Github Copilot) w/ disclosure. Use of AI without disclosure is a violation of the academic integrity policy. Disclosure about your use of AI should be documented in a file named `ai_disclosure.md` in the main directory of your repository. (Create this file if you need to via "Add File" > "Create File"!)

Grading of homeworks will involve whether: (1) your program outputs the correct answer, (2) your code follows good coding practices,
and (3) if everything is properly commented.

### Ground Rules

1. This is an **individual homework assignment** without any collaboration allowed. The sharing of code, and talking with 
others about how to code something and copying their response line-by-line, is strictly prohibited. 
But you are encouarged to utilize our D2L discussion board for clarifications!

2. **AI w/ Disclousure** is allowed. (See above in Overview.) 

3. **You may not incorporate into your code any concept that we have not yet covered in the course, or else points will be deducted.**

## The assignment
[decorations.py] 

Prompt and input two integers from the user to represent a date. For example, 10 and 31 will represent `October 31`.

Create a function that has the function header:

`def print_decorations(month,day):` 

that will print out any decorations that we might expect to see around WCU based on the passed arguments. The function won't have a return (it will implicitly return `None`). It will output (via `print`) statements any of the following decorations. Multiple decorations may be printed for a given date.

**Make sure the output decorations match exactly (spacing and capitalization). Also make sure you call your `print_decorations` function with 2 arguments.** Use our D2L discussion board if you have questions!


|Decoration | Dates|
|-----|-----|
|Spooky Things|Oct. 3 - Nov. 5|
Turkeys       |         Oct. 28 - Nov. 28
Strings of Lights |   Nov. 15 - Jan. 4
U.S. Flags          |   June 21 - July 10
Personal            |   Any other date (only if none of the other date ranges apply)

### Invalid Input and Invalid Dates

You do not have to check for invalid dates, such as `3 40` (for March 40th), and I won't be testing for that. Feel free to handle them if you wish.

But your program should output `error: integers expected` if the user enters non-integers, such as `October 31`.

## Submission instructions

We will be using the same submission instructions as in Homework 1

1. Accept this assignment by following the homework link in D2L (you already did this!)
2. Create a `decorations.py` file on your own computer in Visual Studio Code and implement the coding assignment as described above
3. Test it out locally with different values 
4. In your GitHub repository, edit the `decorations.py` file. Copy and paste your code from your local Visual Studio Code into the GitHub text editor. Click on the green "Commit changes" button.
5. With this commit, your code is now submitted and tests are automatically being run on it. The test results can be found 
under the "Actions" menu. Take a look at the test results to see if all the tests are passing.


## Grading

The grade for this homework will be based on the following dimensions:
* 50% - program correctness (e.g. "does it work correctly?", etc.)
Your program must run. If there are errors and your code does not run, this category is a 0%.
* 30% - coding style (e.g. "do variables have good names?", "is there anything in this code that we haven't learned yet?" etc.)
* 20% - comments (e.g. "is the overall file commented?", "are there header comments (name, date, etc.)?", "are there any areas of code where comments could help a person looking at the code understand it easier?")

### Late Policy

The late policy is stated on the syllabus. Late submissions are penalized by a percentage for each day late. The due date for the assignment can be found in the D2L course calendar.
