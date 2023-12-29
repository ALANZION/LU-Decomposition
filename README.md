# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. get the input
2. loop through each row and column
3. use nested loops to perform gaussian elimination
4. prin the result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ALAN ZION H
RegisterNumber: 212223240004
*/
```
from scipy.linalg import lu
import numpy as np

arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ALAN ZION H
RegisterNumber: 212223240004
*/
```
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

## Output:
![Screenshot 2023-12-29 224145](https://github.com/AkilaMohan/LU-Decomposition/assets/145743064/f0e58ebb-1445-4615-9da9-5329b43f1d70)

![Screenshot 2023-12-29 224214](https://github.com/AkilaMohan/LU-Decomposition/assets/145743064/f927ba28-5ce3-49f7-b864-da69317d3cd3)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

