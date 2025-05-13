# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Get the input matrix using np.array()   
### Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
### Step 3:
Print the norm of the matrix in two decimal places.
### Step 4:
End the program.
## Program:
```Python
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
norm = np.linalg.norm(mat,ord=np.inf)

print('{:.2f}'.format(norm))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-24 224813](https://github.com/gauthamkrishna7/Norm-of-a-matrix/assets/141175025/ba732842-7de7-43bb-8e6c-d0ebaf8c2411)

### 2-Norm of a Matrix
![Screenshot 2023-12-24 224915](https://github.com/gauthamkrishna7/Norm-of-a-matrix/assets/141175025/5d0e9d6e-d9fb-4b47-a574-588a974fb3dc)

### Infinity Norm of a Matrix
![Screenshot 2023-12-24 224946](https://github.com/gauthamkrishna7/Norm-of-a-matrix/assets/141175025/8226cf73-f54e-401c-a8c9-e130d648c727)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
