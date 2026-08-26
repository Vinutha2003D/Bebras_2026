---
id: 2026-UK-07
name: Beavers Backpack
title: Beavers Backpack SSI
ages:
  6-8: --
  8-10: --
  10-12: easy
  12-14: --
  14-16: --
  16-19: --
answer_type: multiple choice
categories:
  - data structures and representations
contributors:
  - 

support_files:
  - 

equivalent_tasks: --
settings:
  default_image_scale: 0.18
---


## Body

Tools are stored in a backpack.

Tools are placed on top of each other in the backpack using two commands: PACK and
USE.
- PACK X places tool X on top of any items in the stack.
- USE removes the tool from the top of any items in the backpack
- If the backpack is empty, USE does nothing.

The backpack is packed using the following commands:

PACK Hammer

PACK Saw

PACK Rope

USE

PACK Axe

PACK Map

USE

PACK Torch

USE

USE

## Question/Challenge - for the brochures

If the back pack is packed using the following commands, which tools are used in order?

## Question/Challenge - for the online challenge

If the back pack is packed using the following commands, which tools are used in order?

## Interactivity instruction - for the online challenge
--

## Answer Options/Interactivity Description

A) Rope, Map, Torch, Axe
B) Rope, Axe, Map, Torch
C) Rope, Map, Axe, Hammer

## Answer Explanation

The answer is: Rope, Map, Torch, Axe

Track the items in the backpack from top to bottom.

Backpack: (empty)

1. PACK Hammer → Hammer
2. PACK Saw → Saw, Hammer
3. PACK Rope → Rope, Saw, Hammer
4. USE → Rope
    Backpack Saw, Hammer
5. PACK Axe → Axe, Saw, Hammer
6. PACK Map → Map, Axe, Saw, Hammer
7. USE → Map
    Backpack: Axe, Saw, Hammer
8. PACK Torch → Torch, Axe, Saw, Hammer
9. USE → Torch
    Backpack: Axe, Saw, Hammer
10. USE → Axe

Tools used:

Rope, Map, Torch, Axe

Rope, Axe, Map, Torch is incorrect because the second tool used is not the map.

Rope, Map, Axe, Hammer is incorrect because the third tool used is not an axe

## This is Informatics

Solving this task requires students to combine the behaviour of a stack.

A stack is a data structure that stores items in a specific order, where the last item added is
the first item removed. This behaviour is known as Last In, First Out (LIFO). A good everyday example is a stack of trays in a cafeteria or a pile of books. When you add a tray, it goes on the top of the stack, and when you need one, you take the top tray off first. The two main operations on a stack are push, which adds an item to the top, and pop, which removes the item from the top. You can also peek (or top) to look at the top item without removing it, and check whether the stack is empty before trying to remove an item.

Stacks are widely used in computer science because they help computers keep track of information in the correct order. One important use is when a program calls a function. Each time a function starts, information such as its local variables and the point where the program should return is pushed onto the call stack. If that function calls another function, a new set of information is pushed on top of the first. When the function finishes, its information is popped off the stack, allowing the program to continue where it left off. This is especially important in recursion, where a function repeatedly calls itself. Each recursive call creates a new entry on the call stack until the base case is reached. As the recursive calls finish, they are removed from the stack one by one, allowing the final result to be built correctly.

## This is Computational Thinking

In order for you to solve this task they would use abstraction, algorithmic thinking and
evaluation.

For you to solve this task, you would use abstraction to focus on the stack behaviour while
ignoring the story context, recognising that the backpack behaves like a stack.
You would use algorithmic thinking to follow a sequence of stack operations (push (PACK),
pop (USE)) in the correct order and determine the final contents of a backpack after a series
of operations.

Finally, you would use evaluation to decide whether a proposed sequence of operations
produces the correct result, i.e. what tools are used in order, and determine whether a
suggested answer violates LIFO behaviour.

While attempting to solve this task, you create a mental model of what is happening at each
stage of the story. This is in order for you to visualise the contents of the backpack after
every operation and the order in which tools are used.

## Informatics Keywords and Websites
--

## Computational Thinking Keywords and Websites
--

## Wording and Phrases

## Comments
