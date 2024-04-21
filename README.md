# EXP 2 - RANK-OF-A-MATRIX
## DATE: 09.03.2024
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Importing the NumPy library using the statement import numpy as np.
### Step 2: Define a 3x3 matrix A with the specified values.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of matrix A using the print() statement.
### Step 5: End the program.
## Program:
```
#write a program to find the solution to a system of linear equations [5,-3,-10],[2,2,-3],[-3,-1,5]

#prgram to find the rank of the matrix for the given matrix 
#devoleped by : HOSHINI S
#registerNumber:2305003006

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(a)
print("the rank of the matrix a:",rank)
```
## Output:
![WhatsApp Image 2024-04-12 at 22 16 20](https://github.com/hoshiniii/RANK-OF-A-MATRIX/assets/166852545/892951fa-b7dd-433f-a3fb-a76aede883ae)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

