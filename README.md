# LU Decomposition to find L and U matrix

## AIM:
To write a program to find the L and U matrix using LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np.
2. Import lu from scipy.linalg.
3. Declare the array as A.
4. Assign P,L,U (Pivot matrix,L matrix and U matrix) to lu of A.
5. Print L and U
## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: ROHIT JAIN D
#RegisterNumber: 212222230120
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![OUTPUT](./images/output1.png)

## Result:
Thus the program to find the L and U matrix using LU Decomposition of a matrix is written and verified using python programming.

# Using LU Decomposition to solve a matrix

## AIM:
To write a program to solve a matrix using LU Decomposition.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np.
2. Import lu_factor and lu_solve from scipy.linalg.
3. Get the input of A and B matrix.
4. Assign lu and piv (lu and Pivot matrix) to lu_factor of A.
5. Assign x to lu_solve of lu and piv with B and print x.
## Program:
(i) To find the L and U matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: ROHIT JAIN D
#RegisterNumber: 212222230120
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![OUTPUT](./images/output2.png)

## Result:
Thus the program to solve a matrix using LU Decomposition is written and verified using python programming.