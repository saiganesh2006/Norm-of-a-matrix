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
# Register No:212223240025
# Developed By: D.B.V.SAI GANESH
# 1-Norm of a Matrix:
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,1)
norm="{:.2f}".format(ans)
print(norm)

# 2-Norm of a Matrix:
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,2)
norm="{:.2f}".format(ans)
print(norm)

# Infinity Norm of a Matrix:
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,np.inf)
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-22 092318](https://github.com/saiganesh2006/Norm-of-a-matrix/assets/145742342/0ab0945f-9bf7-4104-bbe3-2a420096df81)


### 2-Norm of a Matrix
![Screenshot 2023-12-22 092335](https://github.com/saiganesh2006/Norm-of-a-matrix/assets/145742342/b7edf5cd-a3f2-4e27-bd7d-a5c243db92db)


### Infinity Norm of a Matrix
![Screenshot 2023-12-22 092351](https://github.com/saiganesh2006/Norm-of-a-matrix/assets/145742342/df143664-c3ee-43b2-a3e5-c203c591a64f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.

## DEVELOPED BY: D.B.V.SAI GANESH
## REGISTER NO: 212223240025
