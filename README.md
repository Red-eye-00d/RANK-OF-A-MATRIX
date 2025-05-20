# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Start the program and import the NumPy library.

2. Define the given matrix as a 2D NumPy array.

3. Use the matrix_rank function from NumPy to find the rank of the matrix.

4. Store the result in a variable.

5. Display the rank as output.
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: SUDHARSANAN U
#RegisterNumber:212224230276

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
![image](https://github.com/user-attachments/assets/ec09dcee-a7cf-4e71-814e-d0a4490dfe30)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
