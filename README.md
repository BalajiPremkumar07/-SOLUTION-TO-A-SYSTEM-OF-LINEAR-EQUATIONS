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
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"   
import numpy as np
A = np.array([[1, -3], [3, 1]])
B = np.array([0, 10])
C = np.linalg.solve(A, B)
print(C)

```

## Output:

<img width="1370" height="698" alt="{4FFFB703-C54C-4CF2-A028-4E646ED98895}" src="https://github.com/user-attachments/assets/418d8b01-22e1-48c3-9ce5-9a0b49c8b72f" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

