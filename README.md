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
# Register No: 212224240129
# Developed By: G.Ramanujam
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
Norm_of_Matrix="{:.2f}".format(ans)
print(Norm_of_Matrix)




# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))<img width="1221" height="381" alt="Screenshot 2025-09-18 090949" src="https://github.com/user-attachments/assets/2f59f16b-1cb0-4002-8671-cea63a251465" />

ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```

## Output:
### 1-Norm of a Matrix

<img width="1228" height="814" alt="Screenshot 2025-09-18 090912" src="https://github.com/user-attachments/assets/bc758c66-215d-4e08-80e7-1d594438de4b" />

<img width="1230" height="377" alt="Screenshot 2025-09-18 090924" src="https://github.com/user-attachments/assets/b5eaa5e7-cee9-4503-a0b3-ea357918d548" />


### 2-Norm of a Matrix

<img width="1230" height="881" alt="Screenshot 2025-09-18 090937" src="https://github.com/user-attachments/assets/addd1b0a-040f-4a4e-96a8-5e6ce706c480" />

<img width="1221" height="381" alt="Screenshot 2025-09-18 090949" src="https://github.com/user-attachments/assets/99f50afd-24cf-4dcd-a900-9ba40b069003" />


### Infinity Norm of a Matrix

<img width="1218" height="772" alt="Screenshot 2025-09-18 091002" src="https://github.com/user-attachments/assets/3334a49c-7d6e-4417-b3a8-1a27579617c0" />

<img width="1213" height="335" alt="Screenshot 2025-09-18 091014" src="https://github.com/user-attachments/assets/7d57d449-c663-4977-b837-7d8543908d5b" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
