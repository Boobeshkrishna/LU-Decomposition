# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: BOOBESH PM
RegisterNumber: 212222233001
'''
import numpy as np 
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: BOOBESH PM
RegisterNumber: 212222233001
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv,),b)
print(x)
```

## Output:
![lu decomposition]()
![mat 5 1](https://github.com/Boobeshkrishna/LU-Decomposition/assets/141472052/3c4c9cd8-478d-45b8-a1de-f643d8a18ce6)
![mat 5 2](https://github.com/Boobeshkrishna/LU-Decomposition/assets/141472052/b5a36d56-4362-455f-b769-ed62cf53bd11)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

