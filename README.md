# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
#Program to find the rank of a matrix.
#Developed by: vinodharani
#RegisterNumber:212225040491
```
A = [[3,2,5],
     [1,1,2],
     [3,3,6]]

# Check determinant
det = (A[0][0]*(A[1][1]*A[2][2]-A[1][2]*A[2][1])
      -A[0][1]*(A[1][0]*A[2][2]-A[1][2]*A[2][0])
      +A[0][2]*(A[1][0]*A[2][1]-A[1][1]*A[2][0]))

if det != 0:
    rank = 3
else:
    rank = 2

print(rank)
```
## Output:
<img width="936" height="498" alt="image" src="https://github.com/user-attachments/assets/2c375163-1040-44cd-bde6-0bde2b4888bd" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

