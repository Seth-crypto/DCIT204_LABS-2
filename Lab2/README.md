# DCIT 204 – Lab 2: Interactive Array Algorithms

**Name:** Seth Acheampong
**Student ID:** 22370290

## Overview
This lab implements two interactive console programs in Java using the `Scanner` class for user input.

## Files

### FindMax.java
Finds the maximum value in a user-supplied array and reports its index.
- Prompts for array size, then each element.
- Uses a linear search (O(n)) to find the max value and its index.

**Run:**

```
javac FindMax.java
java FindMax
```
### PairSum.java
Searches for a pair of numbers in the array that sum to a user-given target, using a brute-force nested loop.
- Prompts for array size, elements, and a target sum.
- Uses brute force search (O(n²)) to check every pair.
- Displays the indices, values, and equation if a pair is found; otherwise prints a "no pair found" message.

**Run:**
```
javac FindMax.java
java FindMax
```

## Time Complexity
- FindMax: O(n) — single pass through the array.
- PairSum (Brute Force): O(n²) — nested loop checking every possible pair.
