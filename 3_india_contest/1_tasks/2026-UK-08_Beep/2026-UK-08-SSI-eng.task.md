---
id: 2026-UK-08
name: Beep
title: Beep SSI
ages:
  6-8: --
  8-10: --
  10-12: medium
  12-14: --
  14-16: --
  16-19: --
answer_type: multiple choice
categories:
  - algorithms and programming
contributors:
  - 


support_files:
  - 

equivalent_tasks: --
settings:
  default_image_scale: 0.18
---


## Body

A beaver has written a procedure called Echo.

The procedure follows these rules:
- If the number is 1, it says "BEEP" and stops.
- Otherwise, it:
    1. Says the number.
    2. Uses Echo again with a number that is one smaller.
    3. Says the original number again.

For example, Echo(2) says:

2 BEEP 2

## Question/Challenge - for the brochures

What does Echo(4) say?

## Question/Challenge - for the online challenge

What does Echo(4) say?

## Interactivity instruction - for the online challenge
--

## Answer Options/Interactivity Description

A) 4 3 2 BEEP 2 3 4
B) 4 3 2 1 BEEP 1 2 3 4
C) 4 3 BEEP 3 4
D) BEEP 2 3 4 4 3 2

## Answer Explanation

The answer is: 4 3 2 BEEP 2 3 4

The procedure can be separated into "calling" and "returning" phases.

Echo(4) has the following 15 steps:

Calling the procedure steps 1 to 8

Step 1 Call Echo four

Step 2 Output four

Step 3 Call Echo three

Step 4 Output three

Step 5 Call Echo two

Step 6 Output two

Step 7. Call Echo one

Step 8 Output beep

Returning from the procedure steps 9 to 15

Step 9 Return from Echo one

Step 10 Output two

Step 11 Return from Echo two

Step 12 Output three

Step 13 Return from Echo three

Step 14 Output four

Step 15 Return from Echo four

## This is Informatics

This task introduces recursion and base case.
Recursion is a programming technique where a function solves a problem by calling itself
with a smaller or simpler version of the same problem. Instead of solving the entire problem
at once, recursion repeatedly breaks it down into smaller subproblems until it reaches one
that can be solved directly. A useful way to think about recursion is like a set of Russian
nesting dolls or repeatedly opening smaller boxes inside larger ones. Each recursive call
works on a simpler version of the original problem, and once the simplest problem has been
solved, each previous call finishes its own work until the final answer is produced. Common
examples of recursion include searching through folders, traversing family trees, and
calculating mathematical sequences such as factorials or Fibonacci numbers.

Every recursive function must include a base case, which is the condition that tells the
function when to stop calling itself. Without a base case, the function would continue making
recursive calls indefinitely, eventually causing a stack overflow because the computer runs
out of memory for storing those calls. For example, a recursive function to calculate the
factorial of a number uses the rule factorial(n) = n × factorial(n − 1), but it stops when n = 1
because the factorial of 1 is simply 1. The base case acts as the foundation of the recursive
process, while the recursive case describes how to reduce the problem towards that
foundation. Together, the recursive case and the base case allow recursion to solve complex
problems in a logical, structured, and reliable way.

## This is Computational Thinking

In order for you to solve this task you would use abstraction, pattern recognition,
decomposition, algorithmic thinking, and evaluation.

## Informatics Keywords and Websites
--

## Computational Thinking Keywords and Websites
--

## Wording and Phrases

## Comments
