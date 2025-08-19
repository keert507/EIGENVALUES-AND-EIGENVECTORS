# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2:  Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:  End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: keerthana T
#RegisterNumber: 212224100031

import numpy as np
matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print("Eigen values are", eigenvalues,"and Eigen Vectors are", eigenvectors)
```

## Output:

<img width="1324" height="946" alt="image" src="https://github.com/user-attachments/assets/2bbe12e8-377a-4ee6-b5f8-1d5a4ad164c0" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
