# Exp.No:3a
## STRING - FIND AND REPLACE

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

### ALGORITHM
1. Start and define a function `replacestr(s, d)` that replaces a substring.
2. Take input from the user and store it in variable `a`.
3. Replace the substring `d` in string `s` with the user input `a`, and store the result in `f`.
4. Format and prepare the output showing both the old and new strings.
5. Print the original string `s` and the updated string `f`.

### PROGRAM
```
def replacestr(s,d):
    a=input()
    f=s.replace(d,a)
    print("The old string is {}\nthe new string is {}".format(s,f))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/55271daa-092c-472f-9892-c35ebf3df85e)

### RESULT
Thus a Python function to accept a string, find and replace is successfully implemented.
