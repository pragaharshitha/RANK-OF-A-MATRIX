# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import numpy as np
### Step 2:  Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the program
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: pragaharshitha
#RegisterNumber:22003209
import numpy as np
A = np.array([[1,2,3],[3,6,9]])
B = np.linalg.matrix_rank(A)
print(B)
```
## Output:
![](/rank.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

