# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Define the given 3×3 matrix A using NumPy.

2. Compute the inverse of A using np.linalg.inv(A).

3. Store the result in A_inv.

4. Print the inverse matrix A_inv. 

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

