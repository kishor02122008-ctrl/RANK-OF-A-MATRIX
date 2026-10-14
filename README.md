# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the program and import the required libraries (numpy and os).
### Step 2:Define the input matrix A using np.array(). 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the calculated rank result and terminate the program
## Program:import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[3,2,5],[1,1,2],[3,3,6]])

sol=np.linalg.matrix_rank(A)

print(sol)

## Output:<img width="520" height="673" alt="{CBDCA6D4-7764-4E20-8809-AF3BF6020DDA}" src="https://github.com/user-attachments/assets/30fc8ed6-b1f4-4724-ab2f-037ca5eefb36" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

