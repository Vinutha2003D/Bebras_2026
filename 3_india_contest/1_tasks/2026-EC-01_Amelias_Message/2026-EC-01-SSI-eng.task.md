---
id: 2026-EC-01
name: Amelia's Message
title: Ambika's Message SSI
ages:
  6-8: --
  8-10: --
  10-12: easy
  12-14: --
  14-16: --
  16-19: --
answer_type: multiple choice with images
categories:
  - algorithms and programming
contributors:
  - Omar Paladines, omarpaladines1995@gmail.com, Ecuador (author)
support_files:
  - graphics/*.svg by Omar Paladines

equivalent_tasks: --
settings:
  default_image_scale: 0.40
---


## Body

Ambika sends messages to her friends using a variety of stickers. There are two types of stickers: Animal Stickers and Special Stickers.

Sticker Types: 
- Animal Stickers: Dog, Cat, and Rabbit. 
- Special Stickers: Star, Heart, and Sun. 

Ambika follows specific rules for adding special stickers to the end of her messages based on the animal stickers she uses: 

- If a message contains exactly two animal stickers, Ambika adds a Star sticker at the end. 
- If a message contains exactly three animal stickers, Ambika adds a Heart sticker at the end. 
- If all the animal stickers in a message are different from each other, Ambika adds a Sun sticker at the end. 

Multiple stickers can be applied if multiple rules apply to a message. 

## Question/Challenge - for the brochures

There are four different messages. Based on Ambika’s rules, select the message that was correctly sent by Ambika.

## Question/Challenge - for the online challenge

There are four different messages. Based on Ambika’s rules, select the message that was correctly sent by Ambika.

## Interactivity instruction - for the online challenge
--

## Answer Options/Interactivity Description

A) Message 1: Dog, Cat
B) Message 2: Dog, Dog, Cat, Heart 
C) Message 3: Rabbit, Dog, Sun, Star 
D) Message 4: Dog, Cat, Rabbit, Heart


## Answer Explanation

The correct answer is Message 2.

Message 2 is correct because it contains exactly three animal stickers (Dog, Dog, Cat), so the Heart Rule applies. However, because two of the animals are the same (two Dogs), they are not all different, so the Sun Rule does not apply. The message correctly ends with only a Heart.

Why the other messages are incorrect:
- Message 1 has two different animals, so it is missing both a Star and a Sun sticker.
- Message 3 has two different animals, so it should have both a Star and a Sun sticker at the end. (The source explanation notes that if Ambika sent this, it would require both stickers).
- Message 4 has three different animals, so it is missing a Sun sticker at the end.

Going over all the rules, it follows that only the second message could have been sent by Ambika but the first, third, and fourth messages could not.

## This is Informatics

This task’s solution follows a simple algorithm to determine which messages were sent by Ambika, which consisted of successively testing each of Amelia’s rules against the set of messages and collecting the set of messages that failed any of the rules. This implementation is an example of the use of if-then conditional statements in programming.

More generally, this task is an example of a data validation process, in which some inputs are analyzed to ensure that they conform to some pre-existing rules. In particular, the “stickers”
attached to each input resemble the concept of a checksum used to verify the message's integrity.

## This is Computational Thinking

To solve this task you must use logical reasoning and evaluation.

Using logical reasoning you apply each rule to the messages and decide which conditions
have been met and therefore what stickers should be added to the end of the message.

By following Ambika’s rules, you must then evaluate each option based on whether the
correct stickers have been added to the end of the message or not

## Informatics Keywords and Websites
--

## Computational Thinking Keywords and Websites
--

## Wording and Phrases

## Comments

