---
id: 2026-UK-01
name: Voice Messages
title: Voice Messages SSI
ages:
  6-8: --
  8-10: --
  10-12: hard
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

Beaver Bob has a voice recorder that stores words in the order they are recorded.

He can give three commands:

- RECORD followed by a word adds the word to the end of the list.
- DELETE removes the recorded word from the front of the list.
- PLAY says the recorded word from the front of the list but does not remove it.

The recorder starts with no words stored.

Bob gives these commands:

RECORD APPLE

RECORD TREE

PLAY

DELETE

RECORD RIVER

PLAY

## Question/Challenge - for the brochures

Which two words does the recorder say?

## Question/Challenge - for the online challenge

Which two words does the recorder say?

## Interactivity instruction - for the online challenge
--

## Answer Options/Interactivity Description

A) APPLE, TREE
B) APPLE, RIVER
C) TREE, RIVER
D) TREE, TREE

## Answer Explanation

The two words that the recorder says are: APPLE, TREE.

Let's follow the commands one by one.

- Start: (empty)

1. RECORD APPLE
- Stored words: APPLE
2. RECORD TREE
- Stored words: APPLE, TREE
3. PLAY
- Says APPLE
- Stored words stay the same.
4. DELETE
- Removes APPLE.
- Stored words: TREE
5. RECORD RIVER
- Stored words: TREE, RIVER
6. PLAY
- Says TREE

The recorder says:
APPLE, TREE
The other options are incorrect because of the following reasons:
APPLE, RIVER: APPLE is the first word that is heard when the PLAY command is executed
but the next word in the list is not RIVER.
TREE, RIVER: APPLE is always the first word that the recorder plays.
TREE, TREE: APPLE is always the first word that the recorder plays.


## This is Informatics

This task introduces the idea of a queue (first in, first out) without using technical terminology. Students only need to understand that the recorder always plays and deletes the oldest message first. It provides an introduction to how computers organise and process information.

A queue is a linear data structure that stores items in the order they arrive, following the First In, First Out (FIFO) principle. This means the first item added to the queue is the first item removed, just like people waiting in line for a bus or customers queuing at a supermarket checkout. There are two main operations: enqueue, which adds an item to the rear (back) of the queue, and dequeue, which removes an item from the front. Other useful operations include peek (or front), which lets you view the next item without removing it, and isEmpty, which checks whether the queue contains any items.

Queues are widely used in computer science whenever tasks need to be processed in the order they are received. For example, a printer queue ensures documents are printed in the order users send them, and an operating system may use queues to manage processes waiting for CPU time. Queues are also essential in graph algorithms such as breadth-first search (BFS), where nodes are explored level by level in the order they are discovered. By maintaining a fair and predictable order of processing, queues provide an efficient way to manage data and coordinate tasks in many real-world and computing applications.

## This is Computational Thinking

In order for you to solve this task they would use abstraction, algorithmic thinking and
evaluation.

For you to solve this task, you would use abstraction to focus on the queue behaviour while
ignoring the story context, recognising that the recorder behaves like a queue recording and
storing the words in order.

You would use algorithmic thinking to follow a sequence of queue operations (RECORD,
PLAY and DELETE) in the correct order and determine which words are played after a
series of operations.

Finally, you would use evaluation to decide whether a proposed sequence of operations
produces the correct result, i.e. words in the right order, and determine whether a suggested
answer violates LIFO behaviour.

While attempting to solve this task, you create a mental model of what is happening at each
stage of the story. This is in order for you to visualise the list of words stored on the recorder
after every operation and the order in which the words are played

## Informatics Keywords and Websites


## Computational Thinking Keywords and Websites


## Wording and Phrases

## Comments
