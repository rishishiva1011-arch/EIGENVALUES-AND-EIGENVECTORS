# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy module to use built-in linear algebra functions.
### Step 2: 
Create the matrix using np.array() and store it in a variable A.
### Step 3: 
Use np.linalg.eig(A) to calculate the eigenvalues and eigenvectors of the matrix and store them in variables val and vec.
### Step 4: 
Print the eigenvalues and eigenvectors to display the result.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rishikesh S
#RegisterNumber:212225240118
import numpy as np
A=np.array([[2,2],[1,3]])
val,vec=np.linalg.eig(A)
print(f"Eigen values are {val} and Eigen Vectors are {vec}")
```
## Output:
<img width="621" height="201" alt="EXP-4" src="https://github.com/user-attachments/assets/33919ea5-d7be-4181-87a2-9a879c8b23d7" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
