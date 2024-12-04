# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library
2. import lu from scipy.linalg
3. Get input from the user and print the values of L&U 
4. End the program

## Program:
(i) To find the L and U matrix
```python
/*
'''Program to solve a matrix using LU decomposition.
Developed by: KISHORE.S
RegisterNumber: 24900594'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu_piv=lu_factor(A)
x=lu_solve((lu_piv),B)
print(x)

*/
```
(ii) To find the LU Decomposition of a matrix
```python
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: KISHORE.S
RegisterNumber: 24900594'''

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

*/
```

## Output:
(i) To find the L and U matrix
![Screenshot 2024-12-04 132014](https://github.com/user-attachments/assets/30f36f01-6b46-43a1-809b-29cfcf920b76)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2024-12-04 132052](https://github.com/user-attachments/assets/5789961c-a6ef-4470-b40a-87a99d0e2028)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

