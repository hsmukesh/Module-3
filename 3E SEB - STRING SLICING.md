# Exp.No:3e
## SEB - STRING SLICING

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

### PROGRAM

```
Reg.No: 212222060155
Name: Mukesh HS

import re
a=str(input())
pattern=r'[A-Z]+@'
if re.search(pattern,a):
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT
<img width="924" height="377" alt="image" src="https://github.com/user-attachments/assets/e6ffa97a-0648-4c20-9c87-4d41c2715c33" />

### RESULT
Thus a Python program using regular expressions was executed and implemented successfully.
