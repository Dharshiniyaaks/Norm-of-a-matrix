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
import numpy as np
math = np.array(eval(input()))
ans = np.linalg.norm(math, 1)
N="{:.2f}".format(ans)
print(N)

# 2-Norm of a Matrix
'''
import numpy as np

math = np.array(eval(input()))
ans = np.linalg.norm(math, 2)
N ="{:.2f}".format(ans)
print(N)

# Infinity Norm of a Matrix
import numpy as np

math = np.array(eval(input()))
ans = np.linalg.norm(math, np.inf)
N ="{:.2f}".format(ans)
print(N)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-28 144925](https://github.com/Dharshiniyaaks/Norm-of-a-matrix/assets/155055420/4f9eb1a4-c5ab-45b0-8182-a39e236f6e6d)

### 2-Norm of a Matrix
![Screenshot 2023-12-28 145026](https://github.com/Dharshiniyaaks/Norm-of-a-matrix/assets/155055420/efa7a1a6-ff29-4acb-8e1b-17651cbfa566)

### Infinity Norm of a Matrix
![Screenshot 2023-12-28 145101](https://github.com/Dharshiniyaaks/Norm-of-a-matrix/assets/155055420/3a05f48c-b8d9-4882-a468-2b04e396fd65)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
