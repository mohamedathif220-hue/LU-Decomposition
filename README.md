# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: athif
RegisterNumber: 212225040239
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
from scipy.linalg import lu

A = np.array(eval(input()))

P, L, U = lu(A)

print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: athif
RegisterNumber: 212225040239
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
from scipy.linalg import lu_factor, lu_solve

A = np.array(eval(input()))
b = np.array(eval(input()))

lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)

print(x)
```

## Output:

<img width="1233" height="495" alt="Screenshot 2026-06-01 111958" src="https://github.com/user-attachments/assets/17fc0b9d-c4fc-4e2c-aedd-993b3367632d" />


<img width="1258" height="223" alt="Screenshot 2026-06-01 112103" src="https://github.com/user-attachments/assets/f9b6524d-0695-4238-8df0-e28874863a11" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

