# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import numpy as np from library
### Step 2: 
Assign two list as row and column to a variable
### Step 3:
 Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End of the program
## Program:
~~~
#Program to find the rank of a matrix.
#Developed by: CHARU NETHRA R
#RegisterNumber: 23013558
import numpy as np
A = [[1,2,3],[3,6,9]]
rank = np.linalg.matrix_rank(A)
print(rank)
~~~
## Output:
![output](/rank_output.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

