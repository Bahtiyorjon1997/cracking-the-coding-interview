
# Big O Notation 

**👨‍💻 Author: [Sardor](https://github.com/Sardor-M)**

## What is Big O Notation?

**Big O Notation** is a way to formalize fuzzy counting. It allows us to talk formally about how the runtime of an algorithm grows as the inputs grow. It calculates the time compexity of an algorithm.

## Why do we need Big O Notation?

- To find the:
    - Complexity of the program 
    - Efficiency of the program

## How to calculate Big O Notation? 

- Count the number of operations in the algorithm 
    - **Loop(s)**
- Remove the constants
    - **O(2n) -> becomes O(n)**
- Find the highest order term
    - **O(n^2 + 2n + 1) -> becomes O(n^2)**

> Explained: **O(n^2 + 2n + 1)** in this case **n^2** is the highest order term and the we can always pull out the constant factors. That means the **2n** and **1** can be pulled out and the it becomes **O(n^2)** 

## Big O Notation Rules

- **Rule 1:** Worst Case
- **Rule 2:** Remove Constants
- **Rule 3:** Different terms for inputs
- **Rule 4:** Drop Non Dominants



### References

- [Big O Notation](https://www.youtube.com/watch?v=__vX2sjlpXU)
- [Big O Cheat Sheet](https://www.bigocheatsheet.com/)





