# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy moduke to use the build-in functions for calculations

### Step 2:
Prepare the list for each linear equation and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MOHAMED ARSHADULLAH A
#RegisterNumber: 212224230161
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
result1,result2=np.linalg.eig(A)
print(f"Eigen values are {result1} and Eigen Vectors are {result2}")
```
## Output:

![Screenshot 2025-03-27 180220](https://github.com/user-attachments/assets/37b05a93-a7cc-4420-a4cc-72ca9b712be7)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
