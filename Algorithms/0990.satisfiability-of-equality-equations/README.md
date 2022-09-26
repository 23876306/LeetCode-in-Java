# [990. Satisfiability of Equality Equations](https://leetcode.com/problems/satisfiability-of-equality-equations/)

You are given an array of strings `equations` that represent relationships between variables where each string `equations[i]` is of length `4` and takes one of two different forms: `"x<sub>i</sub>==y<sub>i</sub>"` or `"x<sub>i</sub>!=y<sub>i</sub>"`.Here, `x<sub>i</sub>` and `y<sub>i</sub>` are lowercase letters (not necessarily different) that represent one-letter variable names.

Return `true` _if it is possible to assign integers to variable names so as to satisfy all the given equations, or_ `false` _otherwise_.

**Example 1:**

```
Input: equations = ["a==b","b!=a"]
Output: false
Explanation: If we assign say, a = 1 and b = 1, then the first equation is satisfied, but not the second.
There is no way to assign the variables to satisfy both equations.
```

**Example 2:**

```
Input: equations = ["b==a","a==b"]
Output: true
Explanation: We could assign a = 1 and b = 1 to satisfy both equations.
```

## Solutions
1. [Union Find](./SatisfiabilityOfEqualityEquations.java)
    - Copy from the answer.
    - Runtime: faster than 100%.
    - Memory usage: less than 49.65%.
