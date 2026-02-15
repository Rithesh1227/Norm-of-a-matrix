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
# Register No: 212225220084
# Developed By: Rithesh S
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm="{:.2f}".format(ans)
print(Norm)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm="{:.2f}".format(ans)
print(Norm)




# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,ord=np.inf)
Norm="{:.2f}".format(ans)
print(Norm)



```
## Output:
### 1-Norm of a Matrix
<br>
<img width="673" height="182" alt="image" src="https://github.com/user-attachments/assets/0f29dfac-ab3a-49db-977e-253a1ba5cec9" />

<br>

### 2-Norm of a Matrix
<br>
<img width="537" height="230" alt="image" src="https://github.com/user-attachments/assets/6c474597-8fb5-4be1-8674-eabaae1bd811" />

<br>

### Infinity Norm of a Matrix
<br>
<img width="540" height="187" alt="image" src="https://github.com/user-attachments/assets/be79ad3e-3bbb-4d14-bc73-6da7508e826d" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
