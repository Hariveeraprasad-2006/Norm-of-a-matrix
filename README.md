# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212223240014
# Developed By:Arikatla Hari Veera Prasad
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by:Arikatla Hari Veera Prasad
RegisterNumber:212223240014
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:Arikatla Hari Veera Prasad
RegisterNumber:212223240014
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
# Type your code here
# Infinity Norm of a Matrix
'''
Program to find infinity of a matrix.
Developed by:Arikatla Hari Veera Prasad
RegisterNumber:212223240014
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Hariveeraprasad-2006/Norm-of-a-matrix/assets/145049988/7f4cd020-e904-42e8-9a10-63085bbfa189)
### 2-Norm of a Matrix
![image](https://github.com/Hariveeraprasad-2006/Norm-of-a-matrix/assets/145049988/5d0187bc-e086-4c6e-af71-394253038ea7)
### Infinity Norm of a Matrix
![image](https://github.com/Hariveeraprasad-2006/Norm-of-a-matrix/assets/145049988/a3e64712-e0ae-43bd-a379-a3ea56b5e229)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
