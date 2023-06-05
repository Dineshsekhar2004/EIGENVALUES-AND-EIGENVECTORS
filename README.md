# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Imoprt numpy as np
### Step 2: Assign a variable and store the array of matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Assign a variable and store the array of matrix

## Program:
```
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues, evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)
```

## Output:
![image](https://user-images.githubusercontent.com/119405916/230777445-82e2f165-b660-4042-a17e-fa32bbe45a32.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
