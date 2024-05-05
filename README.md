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
# Register No: 212223230182
# Developed By: Samakash.R.S
# 1-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
n="{:2f}".format(a)
print(n)



# 2-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
print("{:.2f}".format(a))


# Infinity Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
print("{:.2f}".format(a))



```
## Output:
### 1-Norm of a Matrix
 
 ![alt text](<Screenshot 2024-05-05 204209.png>)
<br>

### 2-Norm of a Matrix

![alt text](<Screenshot 2024-05-05 204230.png>)
<br>

### Infinity Norm of a Matrix

![alt text](<Screenshot 2024-05-05 204243.png>)
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
