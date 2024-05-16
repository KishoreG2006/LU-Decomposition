# 5.LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm
1.Read the elements of augmented matrix into arrays a and b
2.Calculate elements of L and U
3.Print elements of L and U
4.Find V by solving LV = B by forward substitution
5.Find X by solving UX = V by backward substitution
6.Print Array X as the solution
## Program:
#i)Program to find L and U matrix using LU decomposition.
Developed by: Navinkumar v
RegisterNumber:212223230141
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
#(ii) To find the LU Decomposition of a matrix
Developed by:Navinkumar v
RegisterNumber:212223230141
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```
## Output:
i)![Screenshot 2024-05-13 102922](https://github.com/navinofficial/LU-Decomposition/assets/151710204/ded79609-1096-4003-9df1-235c771b148b)
ii)![image](https://github.com/navinofficial/LU-Decomposition/assets/151710204/c81151d1-d081-43be-96ff-17f4acc3da1e)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

