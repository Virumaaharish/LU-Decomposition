# EXP NO 4
# DATE : 
# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. To Find L and U matrices with LU Decomposition

Step 1: Get the matrix from the user.

Step 2: Using "from scipy.linalg import lu" to import scipy (LU) module.

Step 3: Using "L,U=lu(a)" we can get the matrix of L and U.

Step 4: Print the result matrices (L and U Matrices).

Step 5: End of the Program.

2. To Find X matrix with LU Decomposition
Step 1: Get the matrix from the user.

Step 2: Using "from scipy.linalg import lu_factor,lu_solve" to import scipy module for factorization and solving X.

Step 3: Using "lu,piv=lu_factor(a)"

Step 4: Print the output(x matrix)

Step 5: End of the Program.

## Program:
(i) To find the L and U matrix

Program to find L and U matrix using LU decomposition.

Developed by: Virumaa harish M

RegisterNumber: 212223230246

import numpy as np   #form numpy input array

from scipy.linalg import lu

arr=eval(input())

A=np.array(arr)

P,L,U=lu(A)

print(L)

print(U)

(ii) Program to find the LU Decomposition of a matrix.

Developed by: Virumaa harish M

RegisterNumber: 212223230246

To print X matrix (solution to the equations)

import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

B=eval(input())

res=lu_factor(A)

solution=lu_solve(res,B)

print(solution)

## Output:
![Screenshot 2024-10-01 093111](https://github.com/user-attachments/assets/30a2c894-642e-4680-bd2c-47fcd9c1fc62)

![Screenshot 2024-10-01 093124](https://github.com/user-attachments/assets/f8246719-d199-45a7-88d6-17354e1fc056)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

