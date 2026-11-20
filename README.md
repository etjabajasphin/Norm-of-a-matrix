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
Python
### Register No:26013543
### Developed By:Mukesh M
### 1-Norm of a Matrix
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,1)
### Norm_of_matrix="{:.2f}".format(ans)
### print(Norm_of_matrix)



### 2-Norm of a Matrix
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,2)
### Norm_of_matrix="{:.2f}".format(ans)
### print(Norm_of_matrix)



### Infinity Norm of a Matrix
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,np.inf)
### print("{:2f}".format(ans))


## Output:
### 1-Norm of a Matrix
<br>
<img width="1087" height="702" alt="image" src="https://github.com/user-attachments/assets/d14e758a-d6e9-427e-a358-3fb322f25721" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="1090" height="732" alt="image" src="https://github.com/user-attachments/assets/8c746ac2-1b21-424b-bdac-eb215f4bd655" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1110" height="697" alt="image" src="https://github.com/user-attachments/assets/cbfc5e83-624a-4f33-978a-1e9f9197e21e" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
