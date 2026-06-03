# Day 2 

## What I Practiced

- Pattern Recognition
- Syntax Warmups
- Sets
- Hash Maps
- Fixed Sliding Window
- Dynamic Sliding Window
- Early Return

## What Clicked 

# Early Return 

Use early Return when the answer is found and there is no reason to continue processing. 

Mental Model:

Find answer -> Stop -> Go Home 

Examples:

- Target found 
- Duplicate found 
- Negative number found 
- Valid pair found 

Pattern Recognition

Problems often contain clues that reveal the correct pattern. 

Examples:

- Consecutive -> Sliding Window
- Longest -> Best Tracking
- Smallest -> Best Tracking
- Duplicate -> Set
- Count -> Counter
- Count each -> Frequency Map
- Sorted Array -> Two Pointers
- Exist? -> Boolean
- Found -> Early Return

## Biggest Realization 

Programming is starting to feel less like memorizing code and more like selecting building blocks. 

The goal is not to memorize every solution.

The goal is to recognize the pattern and assemble the correct blocks. 

Example blocks:

- Filter
- Count
- Boolean
- Best Tracking
- Sets
- Hash Maps
- Sliding Windows
- Two Pointers
- Early Return

What To Work On:

## Set Pattern 

I accidentally wrote:

seen.append(item)

but sets use:

seen.add(item)

## Duplicate Check 

I accidentally checked:

if item in data:

instead of:

if item in seen 

because the question is:

"Have I seen this before?"

not:

"Does this exis in the list?"

## New Vocabulary 

State = information currently being tracked 

Invariant = rule that stays true 

Optimization = reducing unnecessary work 

Frequency Map = item -> count 

Set = unique values only 

Early Return = stop processing once answer is found 

## One Thing I Can Explain 

Fixed Window:

Create the first window.

Remove old value. 

Add new value. 

Track the best result. 

Dynamic Window: 

Expand. 

Repair. 

Continue. 

## Funny Observation 

Today I realized that many real-life problems could benefit from Early Return. 

Find answer. 

Stop. 

Go home. 

## Next Session Goals

- Learn more pattern recognition clues
- Get faster with syntax
- Understand frequency maps deeper
- Build another small sliding window project
- Continue documenting progress in GitHub 
