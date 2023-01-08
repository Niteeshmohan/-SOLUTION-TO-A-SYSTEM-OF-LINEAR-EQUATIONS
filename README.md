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
``` python
#Program to find the solution for the given linear equations.
#Developed by: NITEESH M
#RegisterNumber:22008756
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
sol=np.linalg.solve(a,b)
print(sol)
```

## Output:
![output](https://user-images.githubusercontent.com/119575445/211185463-e6b88873-5821-48fe-9a06-89ed6262c161.png)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

