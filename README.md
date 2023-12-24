# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import maths as numpy 
2. give the input values
3. use eval input
4. print the L and U matrix

## Program:
(i) To find the L and U matrix
```
Developed by:PRIYADHARSHINI S 
RegisterNumber: 23003522
'''
from scipy.linalg import lu
import numpy as np
array=eval(input())
a=np.array(array)
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Developed by:PRIYADHARSHINI S
RegisterNumber:23003522
'''
from scipy.linalg import lu_factor,lu_solve
lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)
```

## Output:
![lu decomposition](/LU1.png)
![lu decomposition](/LU2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

