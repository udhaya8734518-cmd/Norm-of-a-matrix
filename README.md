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
# Register No:UDHAYA GIRI V
# Developed By:25015458
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(norm1)



# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm2=np.linalg.norm(a,2)
print(f"{norm2:.2f}")



# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(f"{b:.2f}")




```
## Output:
### 1-Norm of a Matrix
<img width="1417" height="833" alt="Screenshot 2025-12-05 092511" src="https://github.com/user-attachments/assets/ae379711-90e4-4d0a-b2ac-18d8bab233a8" />


### 2-Norm of a Matrix
<img width="1413" height="842" alt="Screenshot 2025-12-05 092533" src="https://github.com/user-attachments/assets/8b622c5f-c727-43c9-ace9-d935c2663062" />


### Infinity Norm of a Matrix
<img width="1428" height="833" alt="Screenshot 2025-12-05 092609" src="https://github.com/user-attachments/assets/df9d4f54-3658-4fe8-b00c-db4ca10b5099" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
