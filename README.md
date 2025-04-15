# LU Decomposition 
## Name: Iniya E
## Reg no: 212224230096

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Initialize matrices
2. Fill in U (upper triangular matrix)
3. Fill in L (lower triangular matrix)
4. Repeat for all rows and columns

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Iniya E
RegisterNumber: 212224230096

import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:Iniya E
RegisterNumber: 212224230096

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_slove((lu,piv),b)
print(x)
*/
```

## Output:
![lu decomposition]()

![Screenshot 2025-04-15 152313](https://github.com/user-attachments/assets/fe620de6-b047-4460-860e-db57b76dbafa)

![Screenshot 2025-04-15 152259](https://github.com/user-attachments/assets/98ca36bd-0137-47a0-8594-34d556adeca2)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

