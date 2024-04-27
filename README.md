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
```
# Register No:212223240012
# Developed By:ARAVINDAN 
# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.array(mat)
norm= np.linalg.norm(ans,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.array(mat)
norm= np.linalg.norm(ans,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.array(mat)
norm= np.linalg.norm(ans,np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-04-27 094035](https://github.com/Aravindan2006/Norm-of-a-matrix/assets/151760062/5ef0deae-ae56-412f-80be-c7e864dab383)

### 2-Norm of a Matrix

![Screenshot 2024-04-27 094054](https://github.com/Aravindan2006/Norm-of-a-matrix/assets/151760062/261ce714-3c46-418e-8536-59fe31e7e326)


### Infinity Norm of a Matrix

![Screenshot 2024-04-27 094114](https://github.com/Aravindan2006/Norm-of-a-matrix/assets/151760062/c91152fb-1d26-4d64-acb2-8d8437cdaf26)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
