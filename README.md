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
# 1-Norm of a Matrix
```
#python program to find the 1-Norm of a matrix and display the results in two decimal places.
#Developed by:Renuga.S
#Register number:212222230118
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: Renuga.S
RegisterNumber:212222230118 

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```
#program to find the Infinity of a matrix and display the result in two decimal places
#Developed by:Renuga.S
#Register number:212222230118
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:

### 1-Norm of a Matrix
![1 norm of a matrix](https://user-images.githubusercontent.com/119292258/235333638-c3e68cea-5cf3-4a84-b72c-b6283d12f342.png)



### 2-Norm of a Matrix

![2 norm of a matrix](https://user-images.githubusercontent.com/119292258/235333648-f6bdd5ab-7056-4db9-abfd-ce511c4e86a1.png)

### Infinity Norm of a Matrix

![two decimal points](https://user-images.githubusercontent.com/119292258/235333665-220271fa-6f25-4ab2-aad1-be0679eab165.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
