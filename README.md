# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

Import the Numpy library in your python script

### Step 2: 

Define your matrix for which you want to find the eigenvalues and eigenvectors.

### Step 3:

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

Display the results

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Puli Naga Neeraj
#RegisterNumber: 23004033
import numpy as np
a = [[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![Eigenvalues-and-Eigenvectors](https://github.com/PuliNagaNeeraj/EIGENVALUES-AND-EIGENVECTORS/assets/138849173/1ed99c3f-4459-4d0c-98c8-597369d713f9)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
