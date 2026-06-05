# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: gowtham u
RegisterNumber:212225040099
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: gowtham u
RegisterNumber:212225040099
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
 
*/
```

## Output:
<img width="1170" height="186" alt="Screenshot 2026-06-05 231546" src="https://github.com/user-attachments/assets/d8b11440-8307-485e-8ff2-32b21fcd3eb1" />
<img width="1189" height="437" alt="Screenshot 2026-06-05 231532" src="https://github.com/user-attachments/assets/653e8c40-eb30-4f59-aaa3-256bc2249520" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

