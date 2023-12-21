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
# Register No: 23008627
# Developed By: Mani Sri Latha.M

# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

# Infinity Norm of a Matrix
``````
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:

### 1-Norm of a Matrix
![1](https://github.com/Manisrii21/Norm-of-a-matrix/assets/147140163/edb866e8-306b-43c0-9d53-902fb3089fba)

### 2-Norm of a Matrix
![2](https://github.com/Manisrii21/Norm-of-a-matrix/assets/147140163/8171efb0-b4e0-42ba-aaa0-d122d95330bb)

### Infinity Norm of a Matrix
![3](https://github.com/Manisrii21/Norm-of-a-matrix/assets/147140163/dedbd7f0-ea5f-43dc-ab72-a4b248a88980)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
