# Day 5

## What I Practiced

- Pattern Recognition
- State Recognition
- Hash Map Intuition
- Two Sum Foundations
- Frequency Maps
- Early Return Review
- Fixed Window Review
- Dynamic Window Review

---

## What Clicked

### State

State is the information currently being tracked.

A useful question is:

"What information do I need to remember?"

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

### Set vs Hash Map

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

A Hash Map remembers useful information.

---

## Two Sum Intuition

Problem:

Find two numbers that add up to a target.

Example:

target = 9

Current Number = 2

Missing Piece = 7

Mental Model:

Current Piece
+
Missing Piece
=
Target

Question:

"Do I already have the piece that completes the puzzle?"

The goal is not to repeatedly search.

The goal is to remember information that helps solve the problem efficiently.

---

## Biggest Realization

Programming is becoming:

Problem
↓
Pattern
↓
State
↓
Solution

Instead of:

Problem
↓
Random Syntax
↓
Hope

---

## Pattern Recognition Review

Correctly Identified:

- Filter
- Count
- Frequency Map
- Fixed Window
- Dynamic Window
- Two Pointers
- Early Return
- Best Tracking

Need More Practice:

- Best Tracking with Condition
- When Sets are required
- Hash Map problem recognition

---

## One Thing I Can Explain

Difference between Hash Maps and Early Return:

Hash Map:

Find answer efficiently.

Early Return:

Exit efficiently.

They often work together.

Example:

Hash Map:
"Do I have the missing piece?"

Answer:

Yes.

Early Return:

Stop.

Go home.

---

## Funny Observation

Hash Maps and dating have something in common.

The question is not:

"How many candidates exist?"

The question is:

"Do I already have the missing piece that fits?"

---

## Notes

Today I stopped focusing on code and started focusing on information.

The important question is no longer:

"What code should I write?"

The important question is:

"What information should I remember?"

---

## Favorite Quote

"The piece that fits."

This became my mental model for understanding Two Sum.

---

## Next Session Goals

- Learn the actual Two Sum implementation
- Hash Map mastery
- Complexity intuition
- O(1) vs O(n) vs O(n²)
- More State Recognition drills
- Continue building pattern recognition speed
