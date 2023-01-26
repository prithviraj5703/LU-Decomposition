# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy,scipy.linalg python library as n,lu
2. Get input from user as x
3. convert x into array
4. lu() returns three values assign it as p,l,u
5.Then print l matrix and u matrix
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
'''Program to solve a matrix using LU decomposition.
Developed by: Mithra mukundaa S G
RegisterNumber: 22005703
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv), b)
print(x)
*/
```

## Output:
![lu decomposition](https://user-images.githubusercontent.com/121418418/214917822-751faee4-b13e-4007-bf34-15634178d45f.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

