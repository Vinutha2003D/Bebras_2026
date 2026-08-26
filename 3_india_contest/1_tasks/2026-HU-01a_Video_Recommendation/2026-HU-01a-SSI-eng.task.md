---
id: 2026-HU-01a
name: Video Recommendation
title: Book Recommendation SSI
ages:
  6-8: --
  8-10: --
  10-12: easy
  12-14: --
  14-16: --
  16-19: --
answer_type: multiple choice
categories:
  - algorithms and programming
contributors:
  - Zsuzsa Pluhár, pluharzs@ik.elte.hu, Hungary (author)
  - Maria Cepeda, marimar@aurovirtual.com, Mexico (contributor, graphics)
  - Bronius Skūpas, bronius@gmail.com, Lithuania (contributor)

support_files:
  - graphics/*.svg by Maria Cepeda

equivalent_tasks: --
settings:
  default_image_scale: 0.18
---

## Body

An app uses a rule to suggest new books to read: 

If another person has read at least 2 of the same books as you, the app suggests their other books to you (if you have not read them). 

You have recently read these three books: 

  Malgudi Days, Sherlock Holmes, Birbal 

Here is what three other people have read 

Anu: Sherlock Holmes, Birbal, Kalam 
Bela: Malgudi Days, Panchatantra, Birbal 
Charu: Sherlock Holmes, Panchatantra, Kabuliwala

## Question/Challenge - for the brochures

Based on the rule, which books will the app suggest to you to read?

## Question/Challenge - for the online challenge

Based on the rule, which books will the app suggest to you to read?

## Interactivity instruction - for the online challenge
--

## Answer Options/Interactivity Description

A) Malgudi Days and Panchatantra
B) Panchatantra and Kalam
C) Sherlock Holmes and Kalam
D) Kalam and Kabuliwala

## Answer Explanation

Correct answer is B.

The suggested books to read next would be Panchatantra and Kalam

Anu read two books that you also read (Sherlock Holmes and Birbal). She meets the rule! So, the
app recommends her other book: Kalam.

Bela also read two books you read (Malgudi Days, Birbal). She meets the rule too! The app
recommends: Panchatantra.

Charu only read one read you have read (Sherlock Holmes). She doesn't meet the “at least 2” rule, so we don't get her books


## This is Informatics

This task shows how a device such as a Kindle uses either Amazon recommendation engine
or the Goodreads app to suggest the next book for you to read. This is called collaborative
filtering.

The computer looks for “similar persons” who like the same things as you. If they have read
something you haven't read yet, the app suggests it!

While this is great to find things you like, it can also trap you in a filter bubble. This means the app only shows you things you already know, and you might miss out on completely new and different ideas.

## This is Computational Thinking

For you to solve this problem, you would use: pattern recognition, decomposition and
evaluation.

With pattern recognition, you must identify books that are repeated between the user's
viewing history and that of Anu, Bela and Charu. A book match.

Instead of looking at all the people or users at the same time, you broke the big problem into
smaller steps (decomposition): checking Anu’s books, then Bela’s, and finally Charu.

You used an IF-THEN rule: IF they have 2 matches, THEN recommend the book which has
not been read. Students must apply a conditional statement (IF-THEN-ELSE) to each user.
This involves rigorous evaluation of the data against a strict logical constraint, which is the
heart of algorithmic decision-making

## Informatics Keywords and Websites
--

## Computational Thinking Keywords and Websites
--

## Wording and Phrases
--

## Comments
--