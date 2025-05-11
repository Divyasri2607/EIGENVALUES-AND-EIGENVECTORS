# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Divya Sri V
#RegisterNumber: 212224230070
import numpy as np
A= [-2,2,-3],[2,1,-6],[-1,-2,0]
eig_values,eig_vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vectors))
```
## Output:
![Screenshot 2025-05-11 230108](https://github.com/user-attachments/assets/f6c41bcc-65c5-4861-8ba0-edb5616a9d62)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
