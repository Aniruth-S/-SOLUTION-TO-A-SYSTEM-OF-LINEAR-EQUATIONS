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
#Program to find the solution for the given linear equations.
#Developed by: Aniruth.S
#RegisterNumber:212225040020
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
x=np.linalg.solve(A,B)
print(x)
```
## Output:


<img width="1476" height="854" alt="{B3F65386-EE53-40D4-AF07-3759F451ABDE}" src="https://github.com/user-attachments/assets/09dbb60e-2aae-4796-a2f0-125f5a0ce5bb" />


## Result: 


Thus the solutions for the linear equations are successfully solved using python program




