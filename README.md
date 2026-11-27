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
![lu decomposition]() <img width="807" height="257" alt="Screenshot 2026-11-27 090659" src="https://github.com/user-attachments/assets/8dc8fea2-7499-4735-ab4a-bc53577254d5" />
<img width="537" height="111" alt="Screenshot 2026-11-27 090725" src="https://github.com/user-attachments/assets/7de61f62-2a24-4ac2-9a05-7046a263816a" />



                       



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

