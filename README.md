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
# Register No:24000580
# Developed By:R N SOMNATH
# 1-Norm of a Matrix

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
s="{:.2f}".format(a)
print(s)



# 2-Norm of a Matrix

import numpy as np
M=np.array(eval(input()))
a=np.linalg.norm(M,2)
s='{:.2f}'.format(a)
print(s)




# Infinity Norm of a Matrix

import numpy as np
M=np.array(eval(input()))
a=np.linalg.norm(M,np.inf)
s='{:.2f}'.format(a)
print(s)


```
## Output:
### 1-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/4e8539bb-f4c1-4482-8ceb-028640138d6a)

<br>
<br>

### 2-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/5c22cc31-6670-4bf0-8281-b939ba260382)

<br>
<br>

### Infinity Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/64f28ff8-759d-4016-bb77-c33fa2103fc0)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
