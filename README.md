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
/*
Program to find the L and U matrix.
Developed by: vignesh.k
RegisterNumber: 25018207
*/
```
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: vignesh.k
RegisterNumber: 25018207
*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
X=lu_solve((lu,pivot),B)
print(X)
```

## Output:
<img width="1257" height="501" alt="Screenshot 2025-11-24 182849" src="https://github.com/user-attachments/assets/8b139d59-f351-4542-86bf-be7579ee4fd5" />

<img width="1264" height="322" alt="Screenshot 2025-11-24 183259" src="https://github.com/user-attachments/assets/fd73bfb6-f64a-4d0b-83d6-8178f3285f95" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

