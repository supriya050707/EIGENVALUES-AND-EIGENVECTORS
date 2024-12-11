# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy modules as np from python library
### Step 2:
Define the matrix as "a" using np.array([],[],[]).
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Displaying the Eigenvalues and Eignvectors using print function.
## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: supriya S J

#RegisterNumber:24001109

import numpy as np

matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

e_values,e_vectors=np.linalg.eig(matrix)

print("Eigen values are {} and Eigen Vectors are {}".format(e_values,e_vectors))

## Output:
![exp4](https://github.com/user-attachments/assets/869923c4-0f4f-4e43-8d1a-d82b9d2e026a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
