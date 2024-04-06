# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:Prashanth.K
# Developed By:212223230152

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

```



# 2-Norm of a Matrix
```
Register No:Prashanth.K
Developed By:212223230152

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)
```

# Infinity Norm of a Matrix
```
Register No:Prashanth.K
Developed By:212223230152

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-04-06 200042](https://github.com/PRASHANTHRATHI/Norm-of-a-matrix/assets/145743120/4dbd15e9-266a-4088-a9c0-9d1464f868c8)
![Screenshot 2024-04-06 200051](https://github.com/PRASHANTHRATHI/Norm-of-a-matrix/assets/145743120/61033157-c8f0-4310-b6b7-bba3d895de42)



### 2-Norm of a Matrix

![Screenshot 2024-04-06 200059](https://github.com/PRASHANTHRATHI/Norm-of-a-matrix/assets/145743120/b46fe44e-1d31-419e-9784-a556fb1b126c)
![Screenshot 2024-04-06 200106](https://github.com/PRASHANTHRATHI/Norm-of-a-matrix/assets/145743120/43e29967-6db3-4b87-ae48-ae69d11deb11)




### Infinity Norm of a Matrix

![Screenshot 2024-04-06 200115](https://github.com/PRASHANTHRATHI/Norm-of-a-matrix/assets/145743120/f0a9d10a-7119-4162-a7a9-e518f449cca7)
![Screenshot 2024-04-06 200122](https://github.com/PRASHANTHRATHI/Norm-of-a-matrix/assets/145743120/6fe0ef84-3268-4325-94b5-309c8eda30c6)





## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
