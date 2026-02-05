# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library.
### Step 2: Define the square matrix.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and the corresponding eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:LAKSHMI NARASIMAN K 
#RegisterNumber:212225230146

import numpy as np 
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
val,vec=np.linalg.eig(A)
print(f"Eigen values are {val} and Eigen Vectors are {vec}")
```
## Output:
<img width="1378" height="860" alt="image" src="https://github.com/user-attachments/assets/7905efd8-5553-4c81-bb2f-13b7a9caacb6" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
