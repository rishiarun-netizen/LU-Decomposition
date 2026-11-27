# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Input matrix dimensions and initialize augmented matrix and solution vector.

2.Populate the augmented matrix with user inputs.

3.Perform Gaussian elimination to reduce the matrix to upper triangular form, ensuring no division by zero.

4.Back substitute to compute solution values for the variables.

5.Print the solution vector formatted to two decimal places.

  

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Rishi Arun.S
RegisterNumber: 26013829
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Rishi Arun.S 
RegisterNumber: 26013829
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu,solve
A=np.array(eval(input()))
B=np.array(eval(input()))
print(np.linalg.solve(A,B))
*/
```

## Output:
![lu decomposition]() "C:\Users\acer\Pictures\Screenshots\Screenshot (15).png""C:\Users\acer\Pictures\Screenshots\Screenshot (16).png"
                       



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

