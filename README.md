# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program.
2.Input the values. 
3.Display the program. 
4.Stop the program. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:D.R.Vinutha 
RegisterNumber:21005742
*/

```
import numpy as np

import scipy

from scipy.linalg import lu

A =eval(input())

P,L,U=lu(A)

print(L)

print(U)

## Output:
![lu decomposition](https://github.com/VINUTHNA-2004/LU-Decomposition/blob/main/Screenshot%20(41).png?raw=true)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: D.R.Vinutha
RegisterNumber: 21005742
*/

```
import numpy as np

from scipy.linalg import lu_factor,lu_solve

A =eval(input())

B =eval(input())

lu,piv= lu_factor(A)

x= lu_solve((lu,piv),B)

print(x)

## Output:
![lu decomposition](https://github.com/VINUTHNA-2004/LU-Decomposition/blob/main/Screenshot%20(42).png?raw=true)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

