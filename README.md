# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Define the matrix 
𝐴
A.

2. Compute eigenvalues and eigenvectors using np.linalg.eig(A).

3. Extract eigenvalues.

4. Extract eigenvectors.

5. Print the eigenvalues and eigenvectors.

## Program:
import numpy as np


A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0,  0, 3]])


eigenvalues, eigenvectors = np.linalg.eig(A)


print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")


## Output:
![Screenshot 2025-04-11 220123](https://github.com/user-attachments/assets/6fd8a43c-600e-421b-8e05-3f8f83e068a9)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program

