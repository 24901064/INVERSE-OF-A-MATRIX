# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. start
2. import the numpy library to work with matrices
3. define the matrix A with the given elements
4. check if the determinant is zero
5. find the inverse of matrix a using np.linalg.inc(A)
6. display the inverse of matrix
7. end

## Program:
import numpy as np


A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])


det = np.linalg.det(A)

if det == 0:
    print("The matrix is not invertible (determinant is zero).")
else:
    # Calculate the inverse
    A_inv = np.linalg.inv(A)
    print("Inverse of the matrix:")
    print(A_inv)

## Output:
![Screenshot 2025-04-11 215310](https://github.com/user-attachments/assets/24fbfbc0-e221-41e0-82bc-8eb9d59a77f0)


## Result:
Thus the inverse of given matrix is successfully solved using python program

