# Day 1
### Question:

- Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

- You may assume that each input would have exactly one solution, and you may not use the same element twice.

- You can return the answer in any order.

### Thought process:
- Start from the first element of the list
- If target-element exists as key in a dict, return [index of key from array, index of element from array]
- Else insert element as the key to the dict

### Changes:
- While inserting into the dict, insert index as the value
