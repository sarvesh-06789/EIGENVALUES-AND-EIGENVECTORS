# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: M.Sharveshwaran
#RegisterNumber:212224240150
import numpy as np
matrix = ([[4, 2],[2, 4]])
eigen_value,eigen_vector = np.linalg.eig(matrix)
print(f"Eigen values are {eigen_value} and Eigen Vectors are {eigen_vector}")
```

## Output:
<img width="1265" height="817" alt="math 04" src="https://github.com/user-attachments/assets/39eb7bd8-5160-4462-876c-37c4e977b1d6" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
