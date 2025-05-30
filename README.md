# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
## Step 1:Take user input for a matrix as a string.
## Step 2: Evaluate the string to convert it into a list of lists.
## Step 3: Convert the list of lists into a NumPy array.
## Step 4: Compute the matrix 1-norm using np.linalg.norm with ord=1.
## Step 5: Store the result in a variable.
## Step 6: Print the computed 1-norm.
```
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
## Algorithm:
```
## Step 1: Accept user input of a matrix as a string.
## Step 2: Evaluate the input string using eval() to convert it into a list of lists.
## Step 3: Convert the list of lists into a NumPy array using np.array().
## Step 4: Calculate the matrix 2-norm using np.linalg.norm(matrix, 2), which returns the largest singular value.
## Step 5: Format the result to 2 decimal places using an f-string.
## Step 6 : Print the formatted 2-norm value.
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
## Algorithm:
```
## Step 1: Input the matrix from the user as a string.
## Step 2: Evaluate the input using eval() to get a list of lists.
## Step 3: Convert the list of lists into a NumPy array using np.array().
## Step 4: Compute the infinity norm using np.linalg.norm(matrix, np.inf), which gives the maximum absolute row sum.
## Step 5: Format the result to 2 decimal places using an f-string.
## Step 6: Print the formatted infinity norm.
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
