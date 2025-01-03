## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
(i) 
1. Import numpy as np and from scipy.linalg import lu
2. using np.array store matrix in variable matrix
3. using lu(),we can find lower triangular matrix and upper triangular matrix
4. print the lower triangular matrix and upper triangular matrix

(ii)
1. Import numpy as np and from scipy.linalg import lu
2. using np.array store matrix in variable matrix
3. using lu_solve() the LU decomposition of matrix can be found
4. using lu_solve(),we can find the solution
5. print the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Sadhana S
RegisterNumber: 24001394
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Sadhana S
RegisterNumber: 24001394
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)

*/
```

## Output:
!["Output"](lu.png)

!["Output"](./lusolution.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

