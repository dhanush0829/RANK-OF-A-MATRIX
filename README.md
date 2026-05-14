# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```py
#Program to find the rank of a matrix.
#Developed by: Dhanush m
#RegisterNumber:212225230051
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
<img width="552" height="178" alt="image" src="https://github.com/user-attachments/assets/32fdf98c-bc45-486c-bdf7-653c0ce74350" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

