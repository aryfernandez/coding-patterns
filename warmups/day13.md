# Day 13 – Index, Number, and Coordinates

## Topics Covered

* Retrieval Practice
* Two Sum Review
* Index vs Number
* Array Information
* Hash Map Information
* Coordinates
* Missing Piece Lookup

---

## Core Two Sum Review

Pattern = Missing Piece Lookup

State = Previously Seen Numbers

Information = Number → Index

Key = Number

Value = Index

---

## Major Distinction

There are two different directions of information flow.

### Array Information

Index → Number

Example:

2 → 11

Meaning:

Index 2 contains number 11.

The array naturally gives us location first, then the item.

---

### Hash Map Information

Number → Index

Example:

11 → 2

Meaning:

Number 11 is located at index 2.

The hashmap is designed for quick lookup by number.

---

## Why Number Is the Key

The number is the key because it tells us what we are searching for.

In Two Sum, we ask:

"Have I seen this number?"

The location is the value because once we find the number, we need to retrieve where it was located.

---

## Pattern Recognition Drill

Given:

nums = [5, 3, 8, 2]

target = 10

When current piece = 8:

Missing piece = 2

Hashmap question:

Have I seen 2, and where is it located?

---

## Coordinates

In Two Sum, the "coordinates" are the index.

Without the index, knowing the number exists is not enough because the problem asks for positions, not just values.

---

## Biggest Breakthrough

Array:

Index → Number

Hashmap:

Number → Index

The direction matters.

The array tells us:

"What is at this location?"

The hashmap tells us:

"Where is this number?"

---

## Professor Assessment

Pattern Recognition: A

State Recognition: A

Hash Map Architecture: A

Key vs Value: A

Coordinates Intuition: A

Information Flow: A-

Python Syntax: Developing

### Overall

Successfully reinforced the difference between array information and hashmap information.

Major lesson:

The index is the coordinate, and the number is the search key.
