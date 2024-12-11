# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module as np.array 
### Step 2: 
Define the matrix as "a" using np.array([],[],[])
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Displaying the eigenvalues and eigenvectors using print function

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: supriya S J

#RegisterNumber:24001109

import numpy as np

matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

e_values,e_vectors=np.linalg.eig(matrix)

print("Eigen values are {} and Eigen Vectors are {}".format(e_values,e_vectors))

## Output:
![exp4](https://github.com/user-attachments/assets/3ab0c5b9-f57f-432b-8e1d-700b4cf11f0a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
