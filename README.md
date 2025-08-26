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
#Developed by: SHARAN S
#RegisterNumber: 212224040309
import numpy as np
A = np.array([[5, -3, -10],
              [2, 2, -3],
              [-3, -1, 5]])
B = np.array([-9, 4, -1])
solution = np.linalg.solve(A, B)
print(solution)
```
## Output:
<img width="1244" height="738" alt="Screenshot 2025-08-26 161218" src="https://github.com/user-attachments/assets/1008d070-0b64-4533-b854-13e8e8aec2c8" />



## Result: 
Thus the solutions for the linear equations are successfully solved using python program

