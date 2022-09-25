# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```python
#Program to to find the square root for the given number(newton's method) using function.
#Developed by: yuvabharathib
#RegisterNumber: 22002787
def sqrt():
    x=int(input())
    b=x
    for i in range(10):
        x=0.5*(x+b/x)
    return x
print("Square root of the number:",sqrt())
```

## Output:
![Screenshot from 2022-09-21 18-58-15](https://user-images.githubusercontent.com/113497680/191516902-cc9d909d-2077-4869-9f65-d78a3d7f3b46.png)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
