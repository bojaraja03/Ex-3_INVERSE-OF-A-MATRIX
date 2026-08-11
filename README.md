# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: BOJA RAJA G
#RegisterNumber: 212225230036
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(matrix)
print(inverse)
```
## Output:
<img width="1508" height="844" alt="image" src="https://github.com/user-attachments/assets/cf9a8050-871d-487c-b2da-540a8d69d8bb" />
<img width="1489" height="291" alt="image" src="https://github.com/user-attachments/assets/d976bbc5-b032-48f4-b3d6-3ab2853e5c95" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

