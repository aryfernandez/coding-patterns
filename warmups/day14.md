# Day 14 – Why Coordinates Matter

## Topics Covered

* Retrieval Practice
* Two Sum Review
* State Recognition
* Information Flow
* Coordinates
* Hash Map Construction
* Index + Number Pairing

---

## Core Two Sum Review

Pattern = Missing Piece Lookup

State = Previously Seen Numbers and Their Locations

Information = Number → Index

Key = Number

Value = Index

---

## Warm-Up Review

### Hash Map Question

The hash map answers:

"Have I seen the missing piece?"

If yes:

"Where is it located?"

This reinforces the purpose of the hash map:

Fast retrieval.

---

## State Recognition

After processing:

4

9

2

The hash map should contain:

```text
4 → 0
9 → 1
2 → 2
```

Architecture:

Number → Index

---

## Major Lesson

The array naturally provides:

Index → Number

Example:

```text
3, 15
```

means:

Index 3 contains number 15.

---

## Building the Hash Map

If Python gives:

```text
index = 3
num = 15
```

We store:

```text
15 → 3
```

because the hash map architecture is:

Number → Index

The number is the search key.

The index is the retrieved information.

---

## Why Coordinates Matter

Before:

```python
for num in nums:
```

We only know:

Number

Example:

```text
15
```

After:

```text
Index + Number
```

We know:

```text
3, 15
```

Meaning:

Index 3 contains number 15.

This gives enough information to build:

```text
15 → 3
```

inside the hash map.

---

## Biggest Breakthrough

A key realization:

The purpose of having both index and number is not simply more information.

The purpose is to construct the retrieval system.

Without coordinates:

The number exists.

With coordinates:

The number becomes useful.

Professor Ary quote:

"Without the coordinates it is useless."

---

## Mental Model

Array:

Index → Number

Hash Map:

Number → Index

Array answers:

"What is at this location?"

Hash Map answers:

"Where is this number?"

---

## Professor Assessment

Pattern Recognition: A

State Recognition: A

Hash Map Architecture: A

Information Flow: A

Coordinate Intuition: A+

Python Readiness: A-

### Overall

Successfully understood why index and number must be available simultaneously.

Major lesson:

Coordinates transform information into a usable retrieval system.
