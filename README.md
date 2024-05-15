# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use built-in functions for calculations

### Step 2: 
Preapre the list from linear equation and assign in np.array()

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
Print the eigenvalue and eigenvector. End the program.

## Program:

Developed by: SATHYAA R

RegisterNumber: 212223100052

```
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigvalues,eigvectors=np.linalg.eig(matrix)
print("Eigen values are",eigvalues,"and Eigen Vectors are",eigvectors)
```

## Output:

![alt text](<Screenshot 2024-03-23 183013.png>)
![alt text](<Screenshot 2024-03-23 182952.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
