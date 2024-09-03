# Date:
# Ex.No.4: EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the Numpy Library.
### Step 2: Assign the matirx value.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the values.

## Program:
```
import numpy as np
a=[[4,2],[2,4]]
value,vector=np.linalg.eig(a)
print("Eigen values are",value,"and Eigen Vectors are",vector)
```
## Output:
![Screenshot 2024-09-04 010223](https://github.com/user-attachments/assets/2e6c2ec8-4dd0-4306-872b-3cfdfb7aa2f9)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
