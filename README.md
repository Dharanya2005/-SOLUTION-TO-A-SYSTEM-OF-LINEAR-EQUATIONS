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
#Developed by:DHARANYA.N 
#RegisterNumber:23006980
import numpy as np
A=[[1,-3],[3,1]]
B=np.array([0,10])
C=np.linalg.solve(A,B)
print(C)

```

## Output:
![Screenshot 2023-11-29 114637](https://github.com/Dharanya2005/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145742468/44782b01-a9d0-44e1-8ca9-30fd9caddb55)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

