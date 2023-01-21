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

#developed by:shalini.v
#register numnber:22009257
```py
def square(n,ite):
    m=float(n)
    for i in range(ite):
        n=0.5*(n+m/n)
    print("Square root of the number:",n)
n=int(input())
ite=1000
square(n,ite)
```
## Output:
![square of a number ](/square.jpg)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
