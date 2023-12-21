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
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/138849343/b95cc5de-cf60-49b9-9740-29f5c38b7560)


### 2-Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/138849343/aeb64d4b-c7f3-4acb-9074-7626613db712)


### Infinity Norm of a Matrix
![image](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/138849343/6e3c6578-c7c9-420e-80cb-bfeb5b1447c2)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
