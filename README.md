# Algorithm for QR Decomposition
## Aim:
To implement QR decomposition algorithm using the Gram-Schmidt method.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Intialize the matrix Q and u
2.	The vector u and e is given by

    ![eqn1](./ex4.jpg)

    ![eqn2](./ex6.jpg)

    ![eqn3](./ex3.jpg)

3.	Obtain the Q matrix   
    ![eqn4](./ex1.jpg)
4.	Construct the upper triangular matrix R
    ![eqn5](./ex2.jpg)



## Program:
### Gram-Schmidt Method
```

#Program to find the inverse of a matrix.
#Developed by: b.selvaganesh
#RegisterNumber:24900817
import numpy as np
matrix=np.array([[6,2,3],[3,1,1],[10,3,4]])
inverse=np.linalg.inv(matrix)
print(inverse)





```

## Output

![output](png.3.png)


## Result
Thus the QR decomposition algorithm using the Gram-Schmidt process is written and verified the result.