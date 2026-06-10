# Day 6

## What I Practiced

- Pattern Recognition
- State Recognition
- Hash Map Intuition
- Two Sum Foundations
- Set vs Hash Map
- Pattern Combinations
- Complexity Intuition

---

## What Clicked

### Patterns Can Work Together

A problem is often solved by combining multiple patterns.

Examples:

Duplicate Detection:

- Set
- Boolean
- Early Return

Question:
"Have I seen this before?"

---

Two Sum:

- Hash Map
- Boolean
- Early Return

Question:
"Do I already have the missing piece?"

---

Maximum Sum of Consecutive Values:

- Fixed Window
- Best Tracking

Question:
"What is the best window seen so far?"

---

## State Review

State = information currently being tracked.

Examples:

Largest Even Number

State:
- best_even

Duplicate Detection

State:
- seen values

Frequency Map

State:
- word → count

Fixed Window

State:
- current window sum
- best window sum

Dynamic Window

State:
- left pointer
- values currently in window
- best answer so far

---

## Set vs Hash Map

Set:

Have I seen this before?

Examples:

- duplicate detection
- uniqueness checks

Hash Map:

What information do I know about this?

Examples:

- word → count
- number → index
- employee → salary
- fruit → quantity

Big realization:

A Set remembers existence.

A Hash Map remembers information.

---

## Memory Palace Analogy

Today I realized a Hash Map is similar to a memory palace.

Set:

"I know this exists."

Hash Map:

"I know this exists, where it is, and useful information about it."

The power of a Hash Map comes from fast retrieval.

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
=
Target

The goal is not repeated searching.

The goal is remembering useful information.

---

## Complexity Intuition

Method A:

Search the entire room every time you lose your keys.

Method B:

Always place your keys in the same bowl.

Method B requires less work.

Good systems reduce unnecessary work.

Optimization is often removing work instead of adding work.

---

## Biggest Realization

Programming is becoming:

Problem
↓
Pattern
↓
State
↓
Information
↓
Solution

The more clearly I identify the information I need to remember, the easier the solution becomes.

---

## One Thing I Can Explain

Difference between Set and Hash Map:

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

"The missing piece that fits."

This became my mental model for understanding Two Sum.

---

## Next Session Goals

- Learn the actual Two Sum implementation
- Hash Map mastery
- Complexity intuition
- O(1) vs O(n) vs O(n²)
- More State Recognition drills
- Continue building pattern recognition speed
