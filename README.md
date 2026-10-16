# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library.
### Step 2:  Define the matrix A using np.array().
### Step 3: Use np.linalg.inv() to compute the inverse of the matrix A.
### Step 4:Print the inverse of the matrix. 
## Program:import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
## Output:<img width="925" height="205" alt="image" src="https://github.com/user-attachments/assets/c1d3660a-7cb6-4172-a2d4-460a5802d8ad" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

