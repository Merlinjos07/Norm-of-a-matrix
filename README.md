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

# Register No:212225240084
# Developed By:MERLIN M
# 1-Norm of a Matrix


```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
```



# 2-Norm of a Matrix


```
'''
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''
import numpy as np


mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))


```



# Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))



```


## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1155" height="838" alt="image" src="https://github.com/user-attachments/assets/6f99c3a4-1b47-44da-a073-eaf0cc48825a" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1046" height="732" alt="image" src="https://github.com/user-attachments/assets/af815180-62e0-412b-a198-60858eca2c20" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1348" height="795" alt="image" src="https://github.com/user-attachments/assets/1307f650-c9f4-4f47-8f69-59ed7a8b8800" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
