# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the build-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.inv(),we can find the solution
### Step 4: 
End the program
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: SRI HARI KRISHNA D T 
#RegisterNumber: 212224240160
import numpy as np
matrix = [[2, 1, 1],
          [1, 1, 1],
          [1, -1, 2]]
matrix_np = np.array(matrix)
inverse = np.linalg.inv(matrix_np)
print(inverse)
```
## Output:
![image](https://github.com/user-attachments/assets/19551276-dcf3-4282-9a49-6636899432ce)

## Result:
Thus the inverse of given matrix is successfully solved using python program

