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
```
 Register No:212224240059

 Developed By:JAGANNIVASH U M
```
```py

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```




## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-22 080101](https://github.com/user-attachments/assets/f7a10d46-febd-435d-860f-33b23e5ca7b2)

### 2-Norm of a Matrix
![Screenshot 2025-04-22 080113](https://github.com/user-attachments/assets/34d24954-da8b-4ddb-ae87-e23537c2d7dd)



### 3 Infinity Norm of a Matrix
![Screenshot 2025-04-22 080126](https://github.com/user-attachments/assets/cbe719ff-f03f-4579-bd89-aaf44ed4d6f0)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
