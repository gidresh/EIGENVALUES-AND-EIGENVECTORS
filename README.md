# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2:Prepare the lists from each linear equations and assign in np.array() 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:End the program 

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="996" height="671" alt="{94AA0943-2623-484D-A456-B9A293E4018F}" src="https://github.com/user-attachments/assets/ac15a195-1e48-41b5-9678-68858914d467" />
<img width="1425" height="282" alt="{6D129068-5DBC-4723-A97F-C86590C9EF5E}" src="https://github.com/user-attachments/assets/ce697ef7-0936-4c15-a854-a729a6115370" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
