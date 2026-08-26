---
id: 2026-CH-03a
name: Laptops
title: Laptops SSI
ages:
  6-8: --
  8-10: --
  10-12: medium
  12-14: easy
  14-16: --
  16-19: --
answer_type: multiple choice with images
categories:
  - data structures and representations
contributors:
  - Susanne Thut, susanne.thut@informatik-biber.ch, Switzerland (author, graphics)
  - Giovanni Serafini, giovanni.serafini@inf.ethz.ch, Switzerland (author)
  - Christian Datzko, christian@bebras.services, Hungary (author)
  - Nadine Fröhlich, nadine.froehlich@unibas.ch, Switzerland (author)
  - Masiar Babazadeh, masiar.babazadeh@supsi.ch, Switzerland (author)
  - Yahya Tabesh, editor, yahya.tabesh@gmail.com, Iran (contributor)
  - Ezra Templonuevo, editor, ejtemplonuevo@gmail.com, Philippines (contributor)
support_files:
  - graphics/*.svg by Susanne Thut

equivalent_tasks: --
settings:
  default_image_scale: 0.25
---

## Body

Four students use laptops in their class. At the end of class, they always store their laptops in two boxes: Box 1 and Box 2. Each box can store two laptops each. They place the laptops carefully so that the next day, each student can take their own laptop directly without having to move or rearrange any of the others.

Today, they left the room in this order: 

  Ali, Beena, Chiru, Dev

Based on their timetables, they will arrive tomorrow in this order: 

  Beena, Ali, Dev, Chiru.

## Question/Challenge - for the brochures

How did they arrange their laptops when they left the room?

## Question/Challenge - for the online challenge

How did they arrange their laptops when they left the room?

## Interactivity instruction - for the online challenge
--

## Answer Options/Interactivity Description

A) Box1 - Top - Chiru, Box1 - Bottom - Ali, Box2 - Top - Dev, Box2 - Bottom - Beena
B) Box1 - Top - Beena, Box1 - Bottom - Ali, Box2 - Top - Dev, Box2 - Bottom - Chiru
C) Box1 - Top - Beena, Box1 - Bottom - Chiru, Box2 - Top - Ali, Box2 - Bottom - Dev
D) Box1 - Top - Dev, Box1 - Bottom - Beena, Box2 - Top - Chiru, Box2 - Bottom – Ali

## Answer Explanation

B) is correct.

Beena is the first to enter the room. Since her laptop must be on the top of one of the two boxes, we can immediately discard (A) and (D). The next pupil to enter the room is Ali. He can pick his laptop from the bottom of the green box (C) or from the top of the blue box (B). In this step, we cannot rule out either of the two remaining options. Then, it is the turn of Dev. In either case, he can grab his laptop from the blue box: In (B), the laptop is the one on the top, while in (C) his laptop is the one on the bottom. Finally, Chiru can pick her laptop from the bottom of the green box (C) or from the bottom of the blue one (B). In these two last steps, we were not able to discard any of the two candidate solutions (B) and (C).

To resolve the issue, we need a tiebreaker between (B) and (C). To this end, we need to consider the order in which the pupils left the room. Ali was the first to leave. Therefore, his laptop must be on the bottom of either the green or of the blue box. This requirement is satisfied in option (B) but not in option (C). The correct answer is (B).


## This is Informatics

In this Bebras task pupils put their laptops into two boxes. Laptops that were placed on top of a box last, can be grabbed first. In Computer Science, we call this kind of box a stack. Stacks are one of the most useful data structures when it comes to temporarily store data during a computation. Their underlying principle is called LIFO (last in, first out).

When using a stack, a program can perform two actions: it can push an element at the top of the stack, or it can pop the element that currently is on the top of the stack.
- Dev is the last to put his laptop in the box.
- Dev is the first who has to grab his laptop from the top of the stack. Beena has to wait until Chiru also grabbed her laptop before she can access hers.

This means that only the element at the top of the stack can be directly accessed at any given time. In order to access an element other than the one on the top, all the elements between it and the top of the stack must first be removed.

When working with exactly one stack, we can only pop elements in the reverse order of the push actions. With two stacks with two places each, four elements can be distributed among the stacks in six different ways (see picture at the end of answer explanation section).

## This is Computational Thinking

To solve this laptop puzzle, you had to figure out the relevant rules and mentally simulate exactly what happens when you push and pop the items.

With only four laptops, you might be able to guess the right answer just by using your intuition. However, imagine if there were 100 laptops and 10 boxes! For large puzzles like that, human intuition isn't enough anymore. Computers don't have intuition at all, they require a strict, systematic strategy to find the answer.

Instead of guessing, a computer scientist uses algorithmic thinking to systematically construct and check every possible order. By mapping out all the choices step-by-step (for example, using a branching "tree" diagram), they can confidently find the correct arrangement without missing a single option. When you followed the precise rules to verify that Beena's laptop was on top, followed by Ali's, you were using this exact kind of logical reasoning!

## Informatics Keywords and Websites
--

## Computational Thinking Keywords and Websites
--

## Wording and Phrases
--

## Comments
