# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the necessary libraries, including NumPy for numerical operations. 
2. Define or prompt the user to input a square matrix A. Ensure that the matrix is square as LU decomposition is typically applied to square matrices.
3. Use NumPy functions or libraries such as scipy.linalg.lu to perform LU decomposition.
4. Print or display the resulting lower triangular matrix L and upper triangular matrix U, which represent the LU decomposition of the original matrix A.

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by:ARCHANA.T 
RegisterNumber: 212223240013
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: ARCHANA.T
RegisterNumber:212223240013 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv = lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![LU decomposition 1](https://github.com/ARCHANAT1305/LU-Decomposition/assets/145975189/cd52f2e0-6bfc-4ce4-867a-1d2a277d3a2e)

![lu  decomposition 2](https://github.com/ARCHANAT1305/LU-Decomposition/assets/145975189/fd515954-b2cc-48f6-ba9e-73206eb9dfbc)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

