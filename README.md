# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the prograM
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: MIDHUN S
#RegisterNumber:212224230158

import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
~~~

## Output:
![Screenshot 2025-04-26 104752](https://github.com/user-attachments/assets/d93bf3b1-020c-4a60-82de-17430d960139)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

