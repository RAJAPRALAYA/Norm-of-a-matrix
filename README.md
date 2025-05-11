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
# 1-Norm of a matrix
```
''
#Program to find 2-norm of a matrix.
#Developed by: PRALAYAKAVERI RAJA
#Register number: 212224230202
'''

import numpy as np
matrix=np.array(eval(input()))
res=np.linalg.norm(matrix,1)
print(res)

```

# 2-Norm of a Matrix
```
''
Program to find L2-norm of a matrix.
Developed by: PRALAYAKAVERI RAJA
RegisterNumber: 212224230202
'''
import numpy as np
matrix=np.array(eval(input()))
res=np.linalg.norm(matrix,2)
print(f"{res:.2f}")
```


# Infinity Norm of a Matrix
```
''
Program to find infinity of a matrix.
Developed by: PRALAYAKAVERI RAJA
RegisterNumber: 212224230202
'''
import numpy as np
matrix=np.array(eval(input()))
res=np.linalg.norm(matrix,np.inf)
print(f"{res:.2f}")

```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2025-05-11 103006](https://github.com/user-attachments/assets/bdb6afc8-3722-4d24-939c-64f49b5d6b80)

<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2025-05-11 103124](https://github.com/user-attachments/assets/5a8a1555-2820-4b37-aeb5-de25bc09cbc0)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2025-05-11 103158](https://github.com/user-attachments/assets/c04d6423-d216-4f4f-9198-3ee55cc23975)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
