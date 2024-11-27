# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step1 : Import the numpy module to use the built-in functions for calculation
Step 2: Prepare the lists from each linear equations and assign in np.array()
Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Step 4: End the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: D MEAGESWAR 
RegisterNumber:24900815

import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)


(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:D MEAGESWAR 
RegisterNumber: 24900815


import numpy as np

from scipy.linalg import lu_solve

from scipy.linalg import lu_factor

A=np.array(eval(input()))

b=np.array(eval(input()))

lu,piv=lu_factor(A)

x=lu_solve((lu,piv),b)

print(x)




## Output:
![Screenshot 2024-11-27 142544](https://github.com/user-attachments/assets/e5e541d3-4497-405a-9af6-92e21c3676ed)

![Screenshot 2024-11-27 143000](https://github.com/user-attachments/assets/29a199d5-1f31-4030-8b41-48446fb7e3f6)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

