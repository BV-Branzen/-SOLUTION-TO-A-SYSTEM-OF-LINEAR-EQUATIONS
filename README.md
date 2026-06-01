# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

~~~
Name: Branzen B v
Register No: 212225100005
~~~

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

Write a program to find a solution to a system of linear equations x+3y=5, 2x+5y=-3

~~~
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
B=np.array([-9,4,-1])
C=np.linalg.solve(A,B)
print(C)


~~~

## Output:

<img width="576" height="185" alt="image" src="https://github.com/user-attachments/assets/4cd5159d-f1ed-4883-b44b-4f3b9f03acfb" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

