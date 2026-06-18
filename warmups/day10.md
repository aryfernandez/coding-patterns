# Day 10 – Hash Map Architecture & Key Design

## Topics Covered

* Hash Maps
* Dictionaries
* Key vs Value
* Information Retrieval
* Information Architecture
* Two Sum Foundations
* Retrieval Before Review

---

## Core Framework Review

Problem → Pattern → State → Information → Solution

### Definitions

Pattern = Strategy

State = Information that survives between iterations

Information = Data we intentionally store and retrieve

Solution = The final answer produced by the algorithm

---

## Two Sum Review

### Pattern

Missing Piece Lookup

Mental Model:

Current Piece + Missing Piece = Target

Question:

"What piece completes the puzzle?"

---

### State

Previously Seen Numbers

The algorithm remembers information from earlier iterations.

---

### Information Architecture

Major realization:

A Hash Map is not storing numbers.

A Hash Map stores useful information about numbers.

For Two Sum:

Number → Index

Example:

2 → 0

7 → 1

11 → 2

---

## Day 10 Breakthrough

### The Key Insight

The key is the thing we search for.

The value is the information we want returned.

For Two Sum:

We ask:

"Have I seen 2?"

Therefore:

Number = Key

We want:

"Where was 2?"

Therefore:

Index = Value

Final Architecture:

Number → Index

Key → Value

---

## Mistake That Created Learning

Initial thought:

Index = Key

Number = Value

Why this fails:

The algorithm does not ask:

"Have I seen index 0?"

The algorithm asks:

"Have I seen number 2?"

Because we search by number, the number must be the key.

---

## Real Life Analogies

### Contacts App

Name → Phone Number

Question:

"What is Sarah's number?"

Name is the key because it is what we search for.

---

### Library

Book → Shelf Location

Question:

"Where is this book?"

Book is the key.

Location is the value.

---

### Two Sum

Number → Index

Question:

"Have I seen this number?"

Number is the key.

Index is the value.

---

## Hash Map Vocabulary

Computer Science:

* Hash Map
* Hash Table
* Map

Python:

* Dictionary
* dict
* {}

Example:

seen = {}

Mental Model:

An empty memory palace.

---

## Biggest Breakthrough

"The key is whatever I am searching for."

This is bigger than Two Sum.

It applies to:

* Hash Maps
* Databases
* APIs
* System Design
* Information Retrieval

---

## Professor Assessment

Pattern Recognition: A

State Recognition: A

Information Architecture: A+

Hash Map Intuition: A

Key vs Value Design: A

Complexity Intuition: In Progress

Syntax: B+

### Overall

Successfully identified how to design a hash map by starting with the question being asked.

Major lesson:

Do not ask:

"What information do I have?"

Ask:

"What information am I searching for?"
