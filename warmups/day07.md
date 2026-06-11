# Day 7

## What I Practiced

* Pattern Recognition
* State Recognition
* Hash Map Intuition
* Information Modeling
* Set vs Hash Map
* Two Sum Foundations
* Complexity Intuition

---

## What Clicked

### Pattern vs State

Pattern tells me the strategy.

State tells me what information I am tracking.

Examples:

Problem:
Find the largest even number.

Pattern:

* Best Tracking with Condition

State:

* best_even

---

Problem:
Count occurrences of each fruit.

Pattern:

* Frequency Map

State:

* fruit → count

---

Problem:
Longest substring without repeating characters.

Pattern:

* Dynamic Window
* Set
* Best Tracking

State:

* left pointer
* values in window
* best length

---

## Set vs Hash Map

Set answers:

"Have I seen this before?"

Examples:

* duplicate detection
* uniqueness checks

A Set remembers existence.

---

Hash Map answers:

"What do I know about this?"

Examples:

* word → count
* number → index
* employee → salary
* fruit → quantity

A Hash Map remembers information.

---

## Memory Palace Analogy

Today I realized a Hash Map is similar to an organized memory palace.

Set:

"I know this exists."

Hash Map:

"I know this exists, where it is, and useful information about it."

The power comes from retrieval.

---

## Information Modeling

A Hash Map does not need to store only one piece of information.

Example:

cat →

* count: 2
* positions: 1st and 3rd

dog →

* count: 1
* position: 2nd

bird →

* count: 1
* position: 4th

Big realization:

Hash Maps store information that may be useful later.

---

## Two Sum Mental Model

Example:

target = 9

Current Number = 2

Missing Piece = 7

Question:

"Do I already have the piece that completes the puzzle?"

Mental Model:

Current Piece
+
Missing Piece
=============

Target

The goal is not repeated searching.

The goal is efficient retrieval.

---

## Complexity Intuition

Method A:

Search the entire room every time you lose your keys.

Method B:

Always place your keys in the same bowl.

Method B requires less work.

Optimization often means reducing unnecessary searching.

---

## Biggest Realization

A great Hash Map remembers enough information to solve the problem.

Too little information is useless.

Too much information becomes difficult to manage.

The goal is remembering the right information.

---

## One Thing I Can Explain

Set:

Have I seen this before?

Hash Map:

What do I know about this and how can I retrieve it quickly?

---

## Funny Observation

A Set is a bouncer.

A Hash Map is an elite memory palace.

One remembers that you exist.

The other remembers your entire file.

---

## Favorite Quote

"Hash Maps are elite with just the right amount of information and organization."

---

## MIT Professor Notes

Today I stopped thinking about Hash Maps as a coding structure.

I started thinking about them as a system for organizing and retrieving information efficiently.

---

## Next Session Goals

* Learn actual Two Sum implementation
* Hash Map mastery
* Complexity intuition
* O(1) vs O(n) vs O(n²)
* Information modeling
* Continue improving pattern recognition speed
