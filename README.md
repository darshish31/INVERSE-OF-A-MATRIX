# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Input or define a square matrix. 
### Step 2:Check if the determinant is non-zero (matrix is invertible).
### Step 3:Compute the inverse using a library function or algorithm.
### Step 4:Output the inverse or indicate if it's non-invertible.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:Darshini B
#RegisterNumber:24008783

import numpy as np
matrix = np.array([[1, 0, 3], [-1,2,-2], [2,3,-1]])
try:
    inverse = np.linalg.inv(matrix)
    print(inverse)
except np.linalg.LinAlgError:
    print()

```
## Output:
![image](https://github.com/user-attachments/assets/53709c2b-cbe6-4a86-90ad-7080db02d5b7)

## Result:
Thus the inverse of given matrix is successfully solved using python program

