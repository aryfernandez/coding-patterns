# Day 11 – First Python Translation

## Topics Covered

* Retrieval Practice
* Two Sum Review
* Dictionaries (Hash Maps)
* Key vs Value
* Python Loops
* Translating Algorithms into Code

---

## Warm-Up Retrieval

### Two Sum Foundations

Pattern = Missing Piece Lookup

State = Previously Seen Numbers

Information = Number → Index

Data Structure = Dictionary (Hash Map)

---

## Key Insight Review

For Two Sum:

Number = Key

Index = Value

Why?

Because the algorithm asks:

"Have I seen this number?"

The thing being searched becomes the key.

The information returned becomes the value.

Architecture:

Number → Index

Example:

2 → 0

7 → 1

11 → 2

---

## Major Realization

When designing a hash map:

Do not ask:

"What information do I have?"

Ask:

"What information am I searching for?"

The answer determines the key.

---

## Algorithm Review

Two Sum in English:

1. Create a hashmap.
2. Loop through the array.
3. Calculate the missing piece.
4. Ask if the missing piece has already been seen.
5. If yes:

   * Retrieve the stored location.
   * Return the answer.
6. If no:

   * Store the current number and its location.

---

## First Python Translation

### Step 1

Create a hashmap.

Python:

```python
seen = {}
```

Mental Model:

Empty memory palace.

---

### Step 2

Loop through the numbers.

Initial incorrect attempt:

```python
for seen in nums:
```

Realization:

The loop variable should represent the current number, not the hashmap.

Correct idea:

```python
for num in nums:
```

Read as:

"For each number in nums..."

---

## Loop Simulation

Array:

```python
nums = [2, 7, 11, 15]
```

Loop:

```python
for num in nums:
```

Iteration 1:

num = 2

Iteration 2:

num = 7

Iteration 3:

num = 11

Iteration 4:

num = 15

---

## Important Observation

While the loop provides:

Number

The problem ultimately requires:

Number + Location

Current understanding:

The loop gives the value.

A future lesson will provide both:

Value + Index

This is the next syntax milestone.

---

## Biggest Breakthrough

The variable inside the loop represents:

The current number

Not the dictionary.

This was the first successful step in translating an algorithm into Python syntax.

---

## Professor Assessment

Pattern Recognition: A

State Recognition: A

Information Architecture: A+

Hash Map Design: A

Loop Intuition: A-

Python Syntax: B+

Complexity Intuition: In Progress

### Overall

Successfully began translating the Two Sum algorithm from English into Python.

Major lesson:

The code is becoming a translation of the algorithm rather than something to memorize.
