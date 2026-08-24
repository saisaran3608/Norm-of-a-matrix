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
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
```
Program to find 2-norm of a matrix.
Developed by: SRI SAI SARAN G
RegisterNumber: 212225220103
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1919" height="811" alt="image" src="https://github.com/user-attachments/assets/2d53bbd9-38b3-40d8-9311-e00df9b9f003" />


### 2-Norm of a Matrix
<img width="1461" height="895" alt="image" src="https://github.com/user-attachments/assets/d8389a24-3bb5-489d-ae8f-838f03b36105" />


### Infinity Norm of a Matrix
<img width="1473" height="844" alt="image" src="https://github.com/user-attachments/assets/40bc5f5d-04f4-47cd-a038-d591cd409aed" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
