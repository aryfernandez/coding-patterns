# Day 08 – Two Sum Foundations & Information Architecture

## Topics Covered

* Information Architecture
* Hash Maps
* Two Sum Pattern
* State Recognition
* Complexity Intuition
* Problem → Pattern → State → Information → Solution

---

## Key Realizations

### Programming Framework

Programming is becoming:

Problem → Pattern → State → Information → Solution

Instead of:

Problem → Code

---

### Information Architecture

A Set answers:

"Have I seen this before?"

A Hash Map answers:

"What do I know about this?"

Set = Bouncer

Hash Map = Memory Palace

---

### Day 08 Breakthrough

A Hash Map is not storing numbers.

A Hash Map stores useful information about numbers.

The information stored should be:

* Enough to solve the problem
* Not so much that retrieval becomes messy

---

### Life Parallel

"Maybe my capability wasn't the problem. My RAM was full."

Too much state creates friction.

This applies to:

* Humans
* Programs
* Businesses
* Algorithms

Good information systems store what matters.

---

## Two Sum Pattern

### Pattern

Missing Piece Lookup

---

### Recognition Clue

Current Piece + Missing Piece = Target

Question:

"What would complete this puzzle?"

---

### State

Previously seen numbers

---

### Information Architecture

Item + Location

More formally:

Number → Index

Example:

2 → 0

7 → 1

11 → 2

---

### Key Insight

Without the coordinates (index), the information is incomplete.

For this version of Two Sum, value alone is not enough.

The problem asks for:

Indices

Not values.

---

## Two Sum Simulation

Array:

[5, 3, 8, 2]

Target:

10

### Iteration 1

Current Piece = 5

Missing Piece = 5

Question:

Have I seen 5?

Store:

5 → 0

---

### Iteration 2

Current Piece = 3

Missing Piece = 7

Question:

Have I seen 7?

Store:

3 → 1

---

### Iteration 3

Current Piece = 8

Missing Piece = 2

Question:

Have I seen 2?

Store:

8 → 2

---

### Iteration 4

Current Piece = 2

Missing Piece = 8

Question:

Have I seen 8?

Yes.

8 → 2

Problem solved.

---

## Professor Assessment

Pattern Recognition: A

State Recognition: A

Information Architecture: A+

Complexity Intuition: Developing

Syntax: B+

Overall:

Ready for Day 09 – First Two Sum Implementation

Biggest breakthrough:

Thinking about information that must survive between iterations rather than memorizing code.
