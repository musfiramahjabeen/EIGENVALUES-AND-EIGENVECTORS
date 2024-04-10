# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1.            Hardware – PCs
2.            Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 :

Import the numpy module to use the built-in functions for calculation

### Step 2:

Get the input matrix from the user

### Step 3:

Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:

End the program.

## Program:

```python
# Program to find the eigen values and eigen vectors.
# Developed by: Musfira Mahjabeen M
# RegisterNumber: 212223230130
import numpy as np
A=np.array([[4,2],[2,4]])
eigen_value,eigen_vector=np.linalg.eig(A)
print("Eigen values are",eigen_value,"and Eigen Vectors are",eigen_vector)

```

## Output:

![output](ex4-output.png)

## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program.
