# Exp.No:3d  
## TUPLES - element 'n'  not exists

---

### AIM  
Write a Python program to check whether an element 'n'  not exists and '8' exists within a tuple.


---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
def check(t):
    not_exists='n' not in t
    eight_exists='8' in t
    return not_exists,eight_exists
t=eval(input())
not_exists,eight_exists=check(t)
print(not_exists)
print(eight_exists)

```

### OUTPUT

False
True

### RESULT

<img width="742" height="234" alt="image" src="https://github.com/user-attachments/assets/7b73829a-2db2-4434-83be-727c1497be83" />
