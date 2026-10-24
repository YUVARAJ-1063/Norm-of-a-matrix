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
# Register No:26012582
# Developed By:YUVARAJ C
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
norm="{:.2f}".format(norm1)
print(norm)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
# Type your code here
norm1=np.linalg.norm(a,2)
norm="{:.2f}".format(norm1)
print(norm)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(norm1)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<br><img width="1447" height="852" alt="Screenshot 2026-10-24 090026" src="https://github.com/user-attachments/assets/24c433dd-7b1b-4192-b0a6-d34b07bca654" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1421" height="862" alt="Screenshot 2026-10-24 090228" src="https://github.com/user-attachments/assets/2dea1d38-5cb0-45d8-b43f-29cd98c54950" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1448" height="835" alt="Screenshot 2026-10-24 090329" src="https://github.com/user-attachments/assets/d9a97eae-497d-4dc4-bb30-5728a582e483" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
