## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Algorithm:
### Step 1: import numpy module to use bulit in function
### Step 2: assign matrix Ain np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end of the module 
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: GOKULAN S
#RegisterNumber: 25018529
# The number of linearly independent rows or columns in a matrix
# is known as its rank

import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
rank=np.linalg.matrix_rank(A)
print(rank)
```

## Output:

<img width="1243" height="677" alt="Screenshot 2026-01-30 161810" src="https://github.com/user-attachments/assets/dc8c22bb-c39c-4c6e-9441-5d74a84e5487" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

