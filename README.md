# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1: 
Import the numpy module for matrix calculations.
## Step 2: 
From scipy.linalg import lu,lu_factor,lu_solve.
## Step 3:
Get input for the matrix from the user.
## Step 4:
Provide the variable which is needed to be solved inside the argument of imported function.
## Step 5: 
Run the program.
## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: N.PRAVESH
RegisterNumber: 212223230154
'''
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U = lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: N.PRAVESH
RegisterNumber: 212223230154
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),B)
print(X)
```
## Output:
(i) L and U matrix
![Screenshot 2024-04-19 163953](https://github.com/NPravesh2005/LU-Decomposition/assets/164477756/adabd7ef-34f2-4896-ada7-fc4591c3ecf0)
(ii) LU Decomposition of a matrix
![Screenshot 2024-04-19 164027](https://github.com/NPravesh2005/LU-Decomposition/assets/164477756/203cefe6-be59-42ae-9bda-0d37e0666888)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

