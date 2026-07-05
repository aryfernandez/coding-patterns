# Day 17 – The "Algorithm Sandwich" Breakthrough

## Topics Covered

* Two Sum Planning
* Function Inputs
* Algorithm Architecture
* Retrieval Systems
* Hash Map Initialization
* Pattern Recognition Across Problems

---

## Biggest Breakthrough

Today I realized that algorithms are not isolated pieces of code.

They follow the same overall structure with different ingredients.

I called this the **"algorithm sandwich."**

Instead of memorizing every solution separately, I can recognize the architecture and adjust the pieces that change.

---

## Core Engineering Framework

Problem

↓

Pattern (Strategy)

↓

State (What survives?)

↓

Information (What am I processing?)

↓

Solution

---

## Two Sum Inputs

The function needs:

* A list
* A target

Without both inputs, the problem cannot begin.

---

## First Step of the Algorithm

Create an empty hash map.

The hash map is my retrieval system.

It starts empty because no numbers have been processed yet.

As I iterate through the list, I gradually build my inventory.

---

## Purpose of the Hash Map

The goal is not simply to store information.

The goal is fast retrieval.

The hash map answers:

"Have I seen the missing piece?"

If yes:

"Where is it located?"

---

## Important Sequence

1. Receive the list and target.
2. Create an empty map.
3. Loop through the list.
4. Look at the current number.
5. Calculate the missing piece.
6. Ask the map if the missing piece already exists.
7. If found, return both locations.
8. Otherwise, store the current number and its location.
9. Continue.

The order matters.

Checking the map happens before storing the current number.

---

## Human Translation

Python:

```python
for index, num in enumerate(nums):
```

Human Translation:

"For every number, give me its location too."

This allows me to build:

Number → Index

inside the hash map.

---

## Biggest Mindset Shift

I realized programming is less about memorizing syntax and more about recognizing reusable patterns.

Every problem is built from familiar components.

The "sandwich" stays mostly the same.

Only the ingredients change.

---

## Professor Assessment

Pattern Recognition: A+

Algorithm Design: A

Systems Thinking: A+

Hash Map Intuition: A+

Python Confidence: Improving rapidly

### Overall

Today was the day I realized that many algorithms share the same architecture.

Instead of seeing hundreds of different problems, I am beginning to recognize reusable engineering patterns.
