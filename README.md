# Experiment 22: Alternate Matrix Traversal

## Problem Statement

Given a 2D matrix of $M$ rows and $N$ columns, the task is to print the 2D matrix in an alternate manner.

* **Row 1 (Index 0):** Print Left to Right.
* **Row 2 (Index 1):** Print Right to Left.
* **Row 3 (Index 2):** Print Left to Right.
* And so on...

## Input Format

* The first line contains two integers, $M$ and $N$.
* The next $M$ lines contain $N$ space-separated integers.

## Output Format

Print one line with all elements after the alternate traversal.

### Example 1

**Input:**

```text
2 2
1 2
2 3
```

**Output:**

```text
1 2 3 2
```

**Explanation:**
* Row 0 elements: `1 2`. Printed Left to Right -> `1 2`
* Row 1 elements: `2 3`. Printed Right to Left -> `3 2`
* Final Output: `1 2 3 2`

### Example 2

**Input:**

```text
3 3
1 2 3
4 5 6
7 8 9
```

**Output:**

```text
1 2 3 6 5 4 7 8 9
```
