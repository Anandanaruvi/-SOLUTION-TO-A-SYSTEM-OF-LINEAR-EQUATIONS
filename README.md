# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

## Aim:

To write a python program to find a solution to a system of linear equations.

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step 1: 
Import the numpy package
### Step 2
Get the inverse of matrix
### Step 3: 
find the system of linear equation
### Step 4: 
End the program

## Program:
```python

#Program to find the solution for the given linear equations.
#Developed by:A.Aruvi 
#RegisterNumber:22001229
import numpy as np
A=np.array([[1,3],[2,5],])
B=np.array([5,-3])
sol = np.linalg.solve(A,B)
print(sol)
```

## Output
![](out1.png)
 
## Result file:
Thus the solutions for the linear equations are successfully solved using python program
