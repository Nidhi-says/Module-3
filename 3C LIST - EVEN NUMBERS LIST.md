# Exp.No:3c
## LIST - EVEN NUMBERS LIST

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers from **12** to **N**.

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `13` to `a`:  
   - For each number `i`, check if it is even using `i % 2 != 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

### PROGRAM
```
def createlist(a):
    list=[]
    for i in range(13,a):
        if i%2!=0:
            list.append(i)
    print(list)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/6d2a799f-b7c8-45d5-8211-b903201447b5)

### RESULT
Thus a Python function that accepts a number **N** and creates a list containing all even numbers from **12** to **N** is implemented successfully.
