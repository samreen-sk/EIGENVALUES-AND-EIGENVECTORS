# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import numpy as np 
### Step 2: 
Write the given matrix in nested list format
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Execute the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Shaik Samreen
#RegisterNumber:23013412
import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
b,c=np.linalg.eig(A)
print('Eigen values are',b,'and Eigen Vectors are',c)
```
## Output:
![output](./eigen_values_and_eigen_vectors.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
