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
# Register No: 24006127
# Developed By:RavivarmanVV
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_the_matrix="{:.2f}".format(ans)
print(Norm_of_the_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/b828a20c-1d00-40f7-a715-b313aa503bf6)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/c3b18906-dd22-4f39-ae23-f84086d8f944)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/df65ed3a-18e5-4a5c-8198-3f8993b00f08)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
