# Day 4

## What I Practiced

- Pattern Recognition
- State Recognition
- Hash Map Foundations
- Two Sum Intuition
- Early Return Review
- Sets Review
- Dynamic Window Review

## What Clicked

### State

State is the information currently being tracked.

Before today I focused mostly on patterns.

Today I learned to ask:

"What information do I need to remember?"

Examples:

Largest Even Number:

State:
- best_even

Duplicate Detection:

State:
- seen values

Frequency Map:

State:
- word → count

Fixed Window:

State:
- current window sum
- best window sum

Dynamic Window:

State:
- left pointer
- values currently in window
- best answer so far

## Biggest Realization

Programming is becoming a process of:

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

## Two Sum Intuition

I have not learned the code yet.

But I understand the idea.

Example:

target = 9

Current Number = 2

Missing Piece = 7

Question:

"Do I already have the piece that completes the puzzle?"

The goal is not to search repeatedly.

The goal is to remember useful information.

## Hash Map Mental Model

A Set remembers:

Have I seen this before?

A Hash Map remembers:

What useful information do I know about this?

Examples:

- word → count
- number → index
- employee → salary
- fruit → quantity

## Early Return Review

Early Return is not about finding the answer.

Early Return is about what happens AFTER the answer is found.

Mental Model:

Find answer.

Stop.

Go home.

## Funny Observation

Hash Maps and dating have something in common.

The question is not:

"How many candidates exist?"

The question is:

"Do I already have the missing piece that fits?"

## One Thing I Can Explain

Difference between Hash Maps and Early Return:

Hash Map:

Find answer efficiently.

Early Return:

Exit efficiently.

They often work together.

## Next Session Goals

- Learn the actual Two Sum solution
- Master Hash Maps
- Strengthen State Recognition
- Learn Complexity Intuition
- Continue Pattern Recognition Training
