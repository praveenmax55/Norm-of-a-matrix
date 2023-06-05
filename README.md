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
# Register No:212222240076
# Developed By: PRAVEEN D
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
<br>![Screenshot 2023-06-05 104726](https://github.com/praveenmax55/Norm-of-a-matrix/assets/113497509/ac8677f0-63b6-4fcd-92e7-11aabff5a4a9)



### 2-Norm of a Matrix
<br>![Screenshot 2023-06-05 105028](https://github.com/praveenmax55/Norm-of-a-matrix/assets/113497509/86993eef-af09-4a9b-902c-35b442cc2826)


### Infinity Norm of a Matrix
<br>![Screenshot 2023-06-05 104833](https://github.com/praveenmax55/Norm-of-a-matrix/assets/113497509/026da87c-3005-4c8a-9c1f-cceaf1abbe3a)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
