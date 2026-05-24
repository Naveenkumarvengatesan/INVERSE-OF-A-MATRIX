# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

Step1 : Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each equations and assign in np.array()

Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix

Step 4: End the program

## Program:
~~~

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Given matrix
matrix = np.array([[1, 0, 3],
                   [-1, 2, -2],
                   [2, 3, -1]])

# Find inverse of matrix
inverse_matrix = np.linalg.inv(matrix)

# Print result
print(inverse_matrix)
~~~

## Output:
<img width="957" height="842" alt="Screenshot 2026-05-24 225232" src="https://github.com/user-attachments/assets/d8c2347d-f1b0-46ed-afca-e17cb04335b4" />



## Result:

Thus the inverse of given matrix is successfully solved using python program

