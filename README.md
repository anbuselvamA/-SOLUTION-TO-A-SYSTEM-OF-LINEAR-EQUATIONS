# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
Program to find the solution for the given linear equations.
#Developed by:anbuselvam A 
#RegisterNumber:22009081

import numpy as np
a=([1,3],[2,5])
b=([5,-3])
sol=np.linalg.inv(a).dot(b)
print(sol)
```
##Output:
![Screenshot (85)](https://user-images.githubusercontent.com/119559871/215304888-92d87ed7-db7e-4c34-8213-b00a3999db08.png)





## Result: 
Thus the solutions for the linear equations are successfully solved using python program

