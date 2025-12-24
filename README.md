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
```Py
# Register No:25018773
# Developed By:THANZIL HUSSAIN A
# 1-Norm of a Matrix
```
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
c=(f"{b:.2f}")
print(c)
```
# 2-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
c=f"{b:.2f}"
print(c)
```
# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,ord=np.inf)
c=(f"{b:.2f}")
print(c)
```
## Output:
### 1-Norm of a Matrix

<img width="858" height="652" alt="image" src="https://github.com/user-attachments/assets/b9e80b51-c071-4be9-9400-598fa294da7e" />

### 2-Norm of a Matrix

<img width="788" height="698" alt="image" src="https://github.com/user-attachments/assets/c9cb22e8-6ef0-453c-908f-53445368b2dc" />


### Infinity Norm of a Matrix

<img width="603" height="668" alt="image" src="https://github.com/user-attachments/assets/4bf9977d-104d-4454-baa4-ce7419e3149d" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
