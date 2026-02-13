# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: RATTISH KUMAR SS
#RegisterNumber: 212224230223
import numpy as np
a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
b,c=np.linalg.eig(a)
print(f"Eigen values are {b} and Eigen Vectors are {c}")
```
## Output:
<img width="1348" height="807" alt="Screenshot 2025-11-19 111649" src="https://github.com/user-attachments/assets/12dac8d7-e205-4589-8dde-300509f124e1" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
