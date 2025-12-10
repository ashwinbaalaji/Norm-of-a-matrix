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
# Register No:25011987
# Developed By:ASHWIN BAALAJI V K
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(norm1)



# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")



# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
B=np.linalg.norm(A,np.inf)
print(f"{B:.2f}")




```
## Output:
### 1-Norm of a Matrix

<img width="1915" height="1065" alt="Screenshot 2025-12-10 141029" src="https://github.com/user-attachments/assets/644d3813-310f-43cc-94eb-483beeec9b8f" />


### 2-Norm of a Matrix
 <img width="1919" height="1095" alt="Screenshot 2025-12-10 141044" src="https://github.com/user-attachments/assets/58071ef8-8fe4-436c-b2c2-29746efb67f5" />


### Infinity Norm of a Matrix
 <img width="1919" height="1051" alt="Screenshot 2025-12-10 141105" src="https://github.com/user-attachments/assets/15e8883f-3fcb-411e-9288-c8769fef230c" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
