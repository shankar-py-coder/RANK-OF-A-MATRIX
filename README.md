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
End the Program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: SHANKAR SB
#RegisterNumber: 25017085
import numpy as np
A = np.array([[3, 2, 5],[1, 1, 2],[3, 3, 6]])
rank = np.linalg.matrix_rank(A)
print(rank)


```
## Output:
<img width="1330" height="766" alt="Screenshot 2025-11-19 105629" src="https://github.com/user-attachments/assets/1a9a96c3-8f9b-41fd-9e46-84894dbc9d51" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

