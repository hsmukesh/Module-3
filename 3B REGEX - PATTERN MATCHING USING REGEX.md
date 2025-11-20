# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

### PROGRAM

```
Reg.no: 212222060155
Name: Mukesh HS

import re
a=input()
pattern=r'[A-Z]+_'
if re.search(pattern,a):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="939" height="303" alt="image" src="https://github.com/user-attachments/assets/2ebb8e78-4248-4982-bd22-7e04ae7da9da" />

### RESULT
Thus a Python program using regular expressions was executed and implemented successfully.
