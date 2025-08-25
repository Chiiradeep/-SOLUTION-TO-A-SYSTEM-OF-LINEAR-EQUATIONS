# SOLUTION TO A SYSTEM OF LINEAR EQUATIONS
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
~~~
#Program to find the solution for the given linear equations.
#Developed by: Chiiradeep
#RegisterNumber:212224240028

import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
c=np.linalg.solve(A,B)
print(c)
~~~
## Output:
<img width="951" height="475" alt="image" src="https://github.com/user-attachments/assets/7098d079-372c-4214-adc5-813ae0ea3cfd" />

<img width="907" height="345" alt="Screenshot 2025-08-18 105704" src="https://github.com/user-attachments/assets/f0a8dcd9-d30c-4021-9be4-c35433c2bb3d" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

