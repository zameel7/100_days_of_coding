# DAY 6

### Question

Given a string s consisting of words and spaces, return the length of the 
last word in the string.

A word is a maximal substring consisting of non-space characters only.

### Thought process:

- Strip to remove white space from the start and end
- Split string at " " as ```str.split(" ")```
- Return the length of the last element of split string using ```len``` 
function
