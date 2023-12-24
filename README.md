# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import numpy and other required packages
3. Get input from the user and code the required program
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SETHUKKARASI C
RegisterNumber: 23012881
*/
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
Developed by: SETHUKKARASI C
RegisterNumber: 23012881
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![lu decomposition](<Screenshot 2023-12-24 183351.png>)
![output2](<Screenshot 2023-12-24 183420.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

