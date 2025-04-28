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
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
![Screenshot 2025-04-27 154926](https://github.com/user-attachments/assets/500e5609-82c8-499e-b690-bdb171503862)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
