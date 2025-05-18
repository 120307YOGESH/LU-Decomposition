# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import required libraries numpy and scipy.linalg.

2. Input the matrix/matrices using eval(input()).

3. Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().

4. Print the results L and U matrices or solution X matrix.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Yogesh.S
RegisterNumber: 212224230311
*/

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)


```
(ii) To find the LU Decomposition of a matrix
```
/*

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:



![image](https://github.com/user-attachments/assets/65caedd9-1a3b-4f41-8017-643c3fcc7846)



![image](https://github.com/user-attachments/assets/c1be2e2c-8710-4f84-ab92-03871c94976e)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

