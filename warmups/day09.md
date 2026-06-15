# Day 09 – Two Sum Algorithm Design

## Topics Covered

* Retrieval Practice
* Pattern Recognition
* State Recognition
* Information Architecture
* Two Sum
* Algorithm Design Before Code

---

## Warm-Up Retrieval

### Core Framework

Problem → Pattern → State → Information → Solution

### Key Insight

Programming is becoming less about memorizing syntax and more about understanding:

* What problem am I solving?
* What pattern fits?
* What state must survive?
* What information must be stored?
* How do I retrieve it efficiently?

---

## Two Sum Deep Dive

### Problem

Given an array and a target, find the indices of two numbers that add up to the target.

### Pattern

Missing Piece Lookup

### Recognition Clue

Current Piece + Missing Piece = Target

Question:

"What piece completes the puzzle?"

---

## State

Previously Seen Numbers

The algorithm must remember information from earlier iterations.

Without memory, every iteration starts over and becomes inefficient.

---

## Information Architecture

### Major Breakthrough

A Hash Map is not storing numbers.

A Hash Map stores useful information about numbers.

For Two Sum:

Number → Index

Example:

2 → 0

7 → 1

11 → 2

---

## Important Realization

Without the coordinates (index), the information is incomplete.

A Set could answer:

"Have I seen 8?"

A Hash Map can answer:

"Have I seen 8, and where was it?"

The problem requires indices, not just values.

---

## Algorithm Design (English Version)

Before writing code:

1. Create a Hash Map.
2. Loop through the array.
3. Calculate the missing piece.
4. Ask:

   * Have I already seen the missing piece?
5. If yes:

   * Retrieve its stored location.
   * Return both indices.
6. If no:

   * Store the current number and its location.

---

## Simulation Exercise

Array:

[5, 3, 8, 2]

Target:

10

### Iteration 1

Current Piece = 5

Missing Piece = 5

Question:

Have I seen 5?

No.

Store:

5 → 0

---

### Iteration 2

Current Piece = 3

Missing Piece = 7

Question:

Have I seen 7?

No.

Store:

3 → 1

---

### Iteration 3

Current Piece = 8

Missing Piece = 2

Question:

Have I seen 2?

No.

Store:

8 → 2

---

### Iteration 4

Current Piece = 2

Missing Piece = 8

Question:

Have I seen 8?

Yes.

Hash Map:

8 → 2

Solution Found.

---

## Complexity Intuition

Current Understanding:

The goal is to minimize retrieval time.

Hash Maps feel powerful because they allow information to be retrieved immediately rather than repeatedly searching the entire array.

Future Topic:

O(1) vs O(n) vs O(n²)

---

## Biggest Breakthrough

"Without the coordinates it is useless."

This was the key realization of the lesson.

The value alone is not enough.

The algorithm needs:

Item + Location

to solve the problem efficiently.

---

## Professor Assessment

Pattern Recognition: A

State Recognition: A-

Information Architecture: A+

Algorithm Design: A

Complexity Intuition: Developing

Syntax: B+

### Overall

Successfully designed the complete Two Sum algorithm in plain English before writing code.

Ready for Day 10:

* First Two Sum Implementation
* Hash Map Syntax Mastery
* Complexity Intuition (Part 2)
* O(1) vs O(n) vs O(n²)
