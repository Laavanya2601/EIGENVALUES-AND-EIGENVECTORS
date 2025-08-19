# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functionsm for calculation
### Step 2: using np.array() store the matrix in the variable matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eligenvectors of the matrix

## Program:
```#Program to find the eigen values and eigen vectors.
#Developed by: Laavanya.R
#RegisterNumber:212224230135
import numpy as np
a=np.array([[2,2],[1,3]])
values,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
```

## Output:
<img width="1261" height="788" alt="Screenshot 2025-08-19 095208" src="https://github.com/user-attachments/assets/aac5023c-458d-475a-b4a9-e99520585785" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
