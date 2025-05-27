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
![Screenshot 2025-05-27 110712](https://github.com/user-attachments/assets/fc34cc79-b075-46d5-b92d-fe739554e566)

### 2-Norm of a Matrix
![Screenshot 2025-05-27 110719](https://github.com/user-attachments/assets/0f7c684f-028e-4b85-9312-05c0ec608fa6)

### Infinity Norm of a Matrix
![Screenshot 2025-05-27 110726](https://github.com/user-attachments/assets/4a7db098-bbe1-4c3c-8b3c-aac8413aa90b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
