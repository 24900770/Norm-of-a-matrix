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
# Register No: Hariharan M
# Developed By: 24900770
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
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![exma7!](https://github.com/user-attachments/assets/2e7bdd55-3eb3-4690-af6f-aa6027f4a76e)

### 2-Norm of a Matrix
![exma7#](https://github.com/user-attachments/assets/e28ecab6-ddb5-4c96-a37a-105f193397dd)

### Infinity Norm of a Matrix
![exma7@](https://github.com/user-attachments/assets/fcf0909a-ca7e-4604-99fc-dc54abb9cb2c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
