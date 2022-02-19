# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_inverse(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:#Program to find the inverse of a matrix.
#Developed by: Naramala Niharika

#RegisterNumber:21500912

import numpy as np

A=np.array([[6, 2, 3],[3, 1, 1],[10, 3, 4]])

Inverse=np.linalg.inv(A)

print(Inverse)

## Output:
![output](https://github.com/naramala-niharika/INVERSE-OF-A-MATRIX/blob/main/Screenshot%20(16).png?raw=true)

## Result:
Thus the inverse of given matrix is successfully solved using python program

