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
# Register No:22004880
# Developed By:S.S.SRIRAM
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,2)
print("{:.2f}".format(n))
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/120554177/214801742-94e5afec-d8e7-4303-8ac5-5626eb988f53.png)
### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/120554177/214801823-d3ee2b09-bdaa-46e1-94c1-6b7520ced819.png)
### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/120554177/214801950-ace2ac04-9c5e-4d75-ae62-6af0a120b4f4.png)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
