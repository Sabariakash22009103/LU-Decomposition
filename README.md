# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np and from scipy import lu
2. Get the input of array from the user
3. solve P,L,U and print the values
4. End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Sabari Akash A
RegisterNumber: 212222230124 
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Sabari Akash
RegisterNumber: 212222230124 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
### (i) To find the L and U matrix
![lu decomposition](/output1.png)
### To print X matrix (solution to the equations)
![lu decomposition](/output2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

