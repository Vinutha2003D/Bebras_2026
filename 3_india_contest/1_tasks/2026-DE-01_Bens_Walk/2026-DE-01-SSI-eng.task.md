---
id: 2026-DE-01
name: Ben's Walk
title: Badri's Walk SSI
ages:
  6-8: --
  8-10: --
  10-12: hard
  12-14: medium
  14-16: --
  16-19: --
answer_type: multiple choice
categories:
  - data structures and representations
contributors:
  - Andreas Schneider, as.001-uni@web.de, Germany (author)
  - Susanne Thut, thut@bwinf.de, Germany (contributor, graphics)
  - Michael Weigend, mw@creative-informatics.de, Germany (contributor)
  - Wolfgang Pohl, pohl@bwinf.de, Germany (contributor)
  - Maciej M. Syslo, editor, syslo@ii.uni.wroc.pl, Poland (contributor)
  - Daniel Aagrén Geert, editor, danielaageert@gmail.com, Denmark (contributor)
  - Andrew Csizmadia, andrew.csizmadia@raspberrypi.org, United Kingdom (contributor)

support_files:
  - graphics/*.svg by Susanne Thut
equivalent_tasks: --
settings:
  default_image_scale: 0.50
---


## Body

Badri took a walk through the park and visited five locations: bridge, cave, forest, statute and
waterfall.

Each location has an ID made from the two digits 0 and 1 as indicated in the following table.

Location ID Codes
:------- | :----
Location  | ID
bridge    | 000
cave      | 001
forest    | 0100
statue    | 1001
waterfall | 011000


As he walked, Badri recorded the IDs below, from left to right, in the order he passed the
location is:

00101001001011000000

Badri did not pass any location more than once. 

## Question/Challenge - for the brochures

In which order did Badri visit the five locations?

## Question/Challenge - for the online challenge

In which order did Badri visit the five locations?

## Interactivity instruction - for the online challenge
--

## Answer Options/Interactivity Description

a)	bridge, cave, forest, statute, waterfall
b)	cave, forest, statute, waterfall, bridge
c)	forest, statute, waterfall, bridge, cave
d)	statute, waterfall, bridge, cave, forest
e)	waterfall, bridge, cave, forest, statute


## Answer Explanation

Correct Answer: B

cave, forest, statute, waterfall, bridge

Based on what Badri recorded:

00101001001011000000

The route that he passed would be:

Each location is identified by an ID with different symbols. Let us check Badri’s record of his walk.

00101001001011000000

The first three symbols **001** only match the ID of the cave. None of the other IDs start with
this sequence. Therefore, the cave must be the first site Badri passed by.

**001**01001001011000000

The second symbol in the record starts with 0. Only IDs: **000**, **0100** and **011000** start with 0 and only **0100** matches the sequence in Badri’s record. So the forest came next on Badri’s walk.

001**0100**1001011000000

The third site on Badri’s walk is the statute **1001** as it is the only ID that starts with a 1

0010100**1001**011000000

The fourth location is the waterfall **011000** because it is the only one that starts with 01

00101001001**011000**000

The final location is the bridge **000**. This shares the same start as the previous stop (**010**).
Since we already have the fountain, only the trees are left with this start.

00101001001011000**000**

The walk finally ended at the bridge **000**, as there are only three characters left and they fit
the bridge´s ID.

Therefore, Badri visits the five locations in the following order: cave, forest, statute, waterfall,
and bridge.

None of the other suggested sequences are correct as none of them have the cave to be the
first location to be visited by Badri.


## This is Informatics

You have just decoded a sequence of code words from a continuous code string without separators between the code words. The decoding was possible mainly because the code (the set of site IDs) in this Bebras task is prefix-free: No codeword is a prefix of any other (meaning that no codeword starts with any other codeword).

Prefix-free codes play a crucial role in informatics, mainly for data compression. Their defining property guarantees unique decodability: When a stream of code symbols  – in computing, code symbols are bits very often – is read sequentially from left to right, the boundaries between codewords are unambiguous. At every position in the stream, it is clear where one code word ends and the next begins, without the need for separators or lookahead.

A well-known example for generating prefix-free codes is Huffman coding, developed by David A. Huffman in 1952. This widely used compression method assigns shorter codewords to more frequent symbols and longer codewords to less frequent ones. Huffman codes are specifically constructed to be prefix-free, ensuring that compressed data can be decoded reliably and efficiently.

## This is Computational Thinking

For you to solve Badri’s walk task, they would use abstraction and decomposition.

You need to abstract from task presentation details in order to understand the task
description.

The recorded string is broken down (decomposed) step by step into the code words.

## Informatics Keywords and Websites
--

## Computational Thinking Keywords and Websites
--

## Wording and Phrases
--

## Comments
