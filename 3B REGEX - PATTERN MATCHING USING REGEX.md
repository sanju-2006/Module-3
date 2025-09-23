# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```

import re
a=input()
z="ab{2,3}"
q=bool(re.search(z,a))
if q:
    print("Found a match!")
else:
    print("Not matched!")


```
### OUTPUT

<img width="482" height="189" alt="image" src="https://github.com/user-attachments/assets/021d405c-e347-4728-abac-35c6762069d7" />


### RESULT

Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions is successfully verified
