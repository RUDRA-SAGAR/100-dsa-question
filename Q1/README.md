# Q1 - Two Sum

##  Problem
Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to the target.

---

## Approach
- Used a HashMap (dictionary) to store numbers and their indices
- For each element, calculated the required value (`target - current number`)
- Checked if the required value already exists in the map
- If found → return indices

---

## Time Complexity
O(n)

## Space Complexity
O(n)

---

## Key Learning
- Learned how HashMap helps in reducing time complexity
- Understood how to convert brute force (O(n²)) into optimized solution
- Practiced storing and checking previous elements efficiently

---

## Brute Force Idea
- Check every pair of elements
- Time Complexity: O(n²)
- Not efficient for large inputs

---

## Pattern Identified
 Hashing (Store & Lookup pattern)

---

## Notes
- Always think: "Can I store previous values to optimize?"
