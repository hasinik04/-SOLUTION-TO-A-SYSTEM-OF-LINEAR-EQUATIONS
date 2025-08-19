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
#Developed by: KATHI HASINI
#RegisterNumber: 24000087
import numpy as np

A = np.array([[1, 3], [2, 5]])
B = np.array([5, -3])

solution = np.linalg.solve(A, B)
print(solution)
```
## Output:
<img width="1487" height="1018" alt="Screenshot 2025-08-19 175334" src="https://github.com/user-attachments/assets/fba9ca97-ca2f-4713-8476-5646f1c66fae" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

