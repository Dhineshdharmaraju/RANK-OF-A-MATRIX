# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the required library (numpy) in Python to perform matrix operations.
Step 2: Define the matrix for which the rank is to be calculated
Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix .
Step 4: Display the rank of the matrix as the output.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Dinesh D
#RegisterNumber:212225040079
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
Rank = np.linalg.matrix_rank(A)
print(Rank)
```
## Output:
<img width="1919" height="1079" alt="Screenshot 2026-05-06 194415" src="https://github.com/user-attachments/assets/66b38555-1b88-4346-ad16-0be4a133bd3b" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

