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
### Step 4: End the program

## Program:
# Program to find the eigen values and eigen vectors.
# Developed by: ARUNMOZHI VARMAN T
# RegisterNumber: 23002304
import numpy as np
a = np.array([[4,2],[2,4]])
values,vectors = np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

## Output:![Screenshot 2024-01-02 230858](https://github.com/ArunmozhiVarmanT/EIGENVALUES-AND-EIGENVECTORS/assets/144870523/7970d26e-7377-4173-8592-83f6737d8d57)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
