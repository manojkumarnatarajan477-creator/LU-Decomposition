# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. If there is necessary import numpy.
2. Bring the input using the eval function.
3. And write the functions to perform the sum.
4. Next, Print the Result.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MANOJ KUMAR N
RegisterNumber: 25015346
*/
import numpy as np
from scipy.linalg import lu
matrix=eval(input())
P,L,U=lu(matrix)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MANOJ KUMAR N
RegisterNumber: 25015346
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:

![alt text](Mathsforai-ex5(a).png)
![alt text](Mathsforai-ex5(b).png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

