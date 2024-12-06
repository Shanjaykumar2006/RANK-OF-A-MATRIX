# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the prograM
## Program:
...
import numpy as np
a=np.array( [[1,2,3],[3,6,9]])
solution=np.linalg.matrix_rank(a)
print(solution)
...

## Output:
![Screenshot 2024-11-27 134503](https://github.com/user-attachments/assets/93849501-d982-455d-956f-bfae394e0371)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

