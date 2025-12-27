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
# Register No:25017406
# Developed By:PRIYADHARSHAN.U
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,1)
print(n)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''
import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,2)
print(f"{norm:.2f}")

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,np.inf)
print(n)




```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1919" height="973" alt="Screenshot 2025-12-27 135714" src="https://github.com/user-attachments/assets/8201a9b2-c84e-43d5-9597-819998d233a9" />
<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="1919" height="892" alt="Screenshot 2025-12-27 135751" src="https://github.com/user-attachments/assets/36a1f5be-8455-4149-a96c-af08f346669c" />
<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1919" height="888" alt="Screenshot 2025-12-27 135835" src="https://github.com/user-attachments/assets/cf3092d8-1366-4a87-bfd6-4bf71a2aca90" />
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
