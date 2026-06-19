# Day 12 – Index vs Number and Information Flow

## Topics Covered

* Retrieval Practice
* Two Sum Review
* State Recognition
* Hash Map Architecture
* Index vs Number
* Information Flow
* Separating Related Concepts

---

## Warm-Up Retrieval

### Two Sum Foundations

Key = Number

Value = Index

Pattern = Missing Piece Lookup

State = Previously Seen Numbers

Information = Number → Index

---

## Major Realization

A common source of confusion is mixing together:

* Array Information
* Hash Map Information
* Missing Pieces

These are related but different concepts.

---

## Concept 1: Array Information

The array naturally provides:

Index → Number

Example:

```text
0, 2
1, 7
2, 11
3, 15
```

Interpretation:

Index 0 contains 2

Index 1 contains 7

Index 2 contains 11

Index 3 contains 15

This is location followed by value.

---

## Concept 2: Hash Map Information

The hash map stores:

Number → Index

Example:

```text
2 → 0
7 → 1
11 → 2
15 → 3
```

Interpretation:

Number 2 is located at index 0

Number 7 is located at index 1

Number 11 is located at index 2

Number 15 is located at index 3

This is value followed by location.

---

## Concept 3: Missing Piece

Example:

Target = 15

Current Number = 11

Question:

11 + x = 15

Missing Piece:

4

The missing piece is simply the value being searched for.

A pair such as:

```text
2, 11
```

is not a missing piece.

It simply means:

Index 2 contains the number 11.

---

## Important Distinction

Array:

Index → Number

Hash Map:

Number → Index

The direction matters.

The array tells us:

"What is stored here?"

The hash map tells us:

"Where is this stored?"

---

## State Recognition

Current understanding:

The algorithm keeps track of:

Previously seen numbers and their locations.

Example after processing:

```text
2
7
```

State becomes:

```text
2 → 0
7 → 1
```

This information survives between iterations.

---

## Pattern Recognition Practice

Example:

```python
nums = [4, 6, 8, 10]
target = 14
```

Current Piece:

10

Missing Piece:

4

Question:

Have I already seen 4?

If yes:

Where is 4 located?

This reinforced the core idea:

Fast retrieval is the purpose of the hash map.

---

## Biggest Breakthrough

The student correctly identified:

```text
2, 11
```

as:

Index 2 contains number 11

rather than confusing it with a missing piece.

This created a clear separation between:

* Data in the array
* Data in the hash map
* Values being searched for

---

## Professor Assessment

Pattern Recognition: A

State Recognition: A

Hash Map Architecture: A

Key vs Value: A

Information Flow: A-

Python Syntax: Developing

Complexity Intuition: In Progress

### Overall

Successfully separated three related concepts that previously felt like one:

Array Information

Hash Map Information

Missing Piece Logic

Major lesson:

Not all values in the algorithm serve the same purpose.

Understanding the direction of information flow is becoming more important than memorizing syntax.
