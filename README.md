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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print(f"{two_matrix:.2f}")




# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print(f"{two_matrix:.2f}")





# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print(f"{two_matrix:.2f}")





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/kishorenagarajan08/Norm-of-a-matrix/assets/155753188/27af5565-0fa1-4152-80f9-01b913678df8)

### 2-Norm of a Matrix
![image](https://github.com/kishorenagarajan08/Norm-of-a-matrix/assets/155753188/9ea770e3-ed16-4d84-b543-44cf2268988d)

### Infinity Norm of a Matrix

![image](https://github.com/kishorenagarajan08/Norm-of-a-matrix/assets/155753188/be2d7eba-62cd-481e-be3f-7269bf58b36a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
