# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:G.Hindhu 
#RegisterNumber:23014493
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![eigenmatrix](https://github.com/hindhujanaki/EIGENVALUES-AND-EIGENVECTORS/assets/148514666/4a6e54d7-b9a6-40eb-8ce2-cd4b33950062)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
