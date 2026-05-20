# INVERSE-OF-A-MATRIX
## Aim:To write a python program to find the inverse of a matrix
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy module to use the built in functions for calculation.
### Step 2: Prepare the lists from each linear equations and assign in np.array().
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: End the program.


## Program:
```
#Program to find the inverse of a matrix.
#Developed by: G. SHAWN RONEL
#RegisterNumber:25005544
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
X=np.linalg.inv(A)
print(X)
```
## Output:
<img width="1919" height="1079" alt="Screenshot 2026-05-20 093142" src="https://github.com/user-attachments/assets/0ff5e6d9-19ae-4db6-8d9f-b580224b638b" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

