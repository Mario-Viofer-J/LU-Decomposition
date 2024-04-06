# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' . 
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 
4. print the variable 'X'
## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Mario Viofer J
RegisterNumber: 212223100032
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Mario Viofer J
RegisterNumber: 212223100032
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
b=np.array([4,5,7])
x=np.linalg.solve(a,b.T)
print(x)
```

## Output:
(i) To find the L and U matrix

![image](https://github.com/Mario-Viofer-J/LU-Decomposition/assets/144979232/80dfb79a-aad2-45df-9f24-467210d74109)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/Mario-Viofer-J/LU-Decomposition/assets/144979232/5ddd26e5-7140-45cc-aecd-c96cac686518)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

