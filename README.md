# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required libraries such as os and numpy.
### Step 2: Create a square matrix using the np.array() function and store it in a variable.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the Eigenvalues and Eigenvectors using the print() function.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: ROUNAK SINGH
#RegisterNumber: 212225240125

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a= np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:
<img width="928" height="587" alt="image" src="https://github.com/user-attachments/assets/f869bfb9-4d23-493e-8e5f-4fb6e28231a5" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
