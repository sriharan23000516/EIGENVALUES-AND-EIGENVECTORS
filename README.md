EIGENVALUES-AND-EIGENVECTORS
Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
Algorithm:
Step1 :
Start the program.

Step 2:
prepare the lists from the each inverseof a matrix and design in ip.array().

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Sriharan J V
#RegisterNumber:212223100054
import numpy as np

matrix = np.array([[4, 2], [2, 4]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print("Eigen values are", eigenvalues,"and Eigen Vectors are",eigenvectors)


## Output:

![image](https://github.com/sriharan23000516/EIGENVALUES-AND-EIGENVECTORS/assets/139841769/3024de97-beba-4a44-a8ba-0e4372358de6)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
