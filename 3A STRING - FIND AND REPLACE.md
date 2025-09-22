# Exp.No:3a
## STRING - convert

---

### AIM  
Write a python function "convert" that reads a string and then prints a string that capitalize every other letter in the string.


---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```
def convert(a):
    res=""
    for i in range(len(a)):
        if i%2:
            res=res+a[i].upper()
        else:
            res+=a[i].lower()
    print(res)
```

### OUTPUT

pYtHoN PrOgRaMmInG



### RESULT

<img width="903" height="193" alt="image" src="https://github.com/user-attachments/assets/ff10cc5c-2b0a-4128-8898-89564245e271" />
