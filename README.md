# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. . Import numpy and scipy packages.

2. Read the input matrix as two dimensional array.

3. Call the Built in function lu() to decompose the array.

4. print the output.



## Program:
(i) To find the L and U matrix

Program to find the L and U matrix.

Developed by: vidhyasri.k

RegisterNumber: 22008468
import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)

(ii) To find the LU Decomposition of a matrix


Program to find the LU Decomposition of a matrix.

Developed by: vidhyasri.k

RegisterNumber: 22008468

import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

b=np.array(eval(input()))

lu,piv=lu_factor(A)

x=lu_solve((lu,piv),b)

print(x)


## Output:
To find the L and U matrix
![lu1](https://user-images.githubusercontent.com/119477817/215279992-4959c88c-5a34-478c-b30d-c7f7612a6c9c.png)


 To find the LU Decomposition of a matrix
![lu2](https://user-images.githubusercontent.com/119477817/215280009-c271318d-1732-4467-bde9-b6260f517760.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

