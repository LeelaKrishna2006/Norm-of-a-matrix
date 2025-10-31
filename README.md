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
# 1-Norm of a Matrix

Program to find 1-norm of a matrix.
Developed by: ARANI VENKATA SUNDARA LLELA KRISHNA
RegisterNumber: 212224240013

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

Program to find 2-norm of a matrix.
Developed by: ARANI VENKATA SUNDARA LEELA KRISHNA
RegisterNumber: 212224240013

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

Program to find infinity of a matrix.
Developed by: ARANI VENKATA SUNDARA LEELA KRISHNA
RegisterNumber: 212224240013

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="572" height="213" alt="image" src="https://github.com/user-attachments/assets/1ef8768b-be4a-441f-a06e-c2b1a1f5f899" />


### 2-Norm of a Matrix
<img width="504" height="255" alt="image" src="https://github.com/user-attachments/assets/2991bf6d-aef8-4f72-9b23-6bf9e2f7c11f" />


### Infinity Norm of a Matrix
<img width="547" height="208" alt="image" src="https://github.com/user-attachments/assets/ee1bfa5f-5e21-4b72-8969-3680a971b8eb" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
