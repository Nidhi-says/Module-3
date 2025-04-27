# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
To write a Python program that matches a string starting with T, h, or e using regular expressions.

### ALGORITHM
1. Import the `re` (regular expression) module.
2. Define a pattern `p` as `'^[The]'` to match any string starting with T, h, or e.
3. Take input from the user.
4. Use `re.search(p, input())` to check if the input matches the pattern.
5. Print "Found a match!" if it matches, else print "Not matched!".

### PROGRAM
```
import re
p='^[The]'
if re.search(p,input()):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/f03709de-9d45-4be8-9eb6-94da8b46d645)

### RESULT
Thus a Python program that matches a string starting with T, h, or e using regular expressions is implemented successfully.
