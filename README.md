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
# Register No:212224230075
# Developed By:GOKUL S
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="1173" height="777" alt="image" src="https://github.com/user-attachments/assets/02523f19-9cb8-46c9-9932-6023b38707f8" />


### 2-Norm of a Matrix
<img width="1110" height="834" alt="image" src="https://github.com/user-attachments/assets/51a1f206-9b2a-45a4-a790-f3cf2517c6e8" />

### Infinity Norm of a Matrix
<img width="1205" height="755" alt="image" src="https://github.com/user-attachments/assets/5161642b-b758-4fff-a0b4-009b6ca4f1e0" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
