# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

### ALGORITHM

1. Begin the program.  
2. Accept an integer `n` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `res` with values starting from `5` up to `n`, stepping by `5`.  
4. Return the tuple `res`.  
5. Print the resulting tuple.  
6. Terminate the program.

### PROGRAM
```
n=int(input())
res=tuple(i for i in range(5,n,5))
print(res)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/630c2e4c-4413-4092-8e93-d52c2e5bebeb)

### RESULT
Thus a Python program to create a tuple containing all multiples of 5 up to a given number **N** is successfully implemented.
