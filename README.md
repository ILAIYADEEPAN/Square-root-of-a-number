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
```
# find the square root
#Developer name: ILAIYADEEPAN.K
#Reference number:23013535

def sqrt(n,l):
    x=n
    for i in range (l):
        x=0.5*(x+n/x)
    print("Square root of the number:",x)
a=int(input())
l=100
sqrt(a,l)
```

## Output:
![image](https://github.com/ILAIYADEEPAN/Square-root-of-a-number/assets/147473334/637d220a-8739-499a-a26f-00f108dde1f4)

![image](https://github.com/ILAIYADEEPAN/Square-root-of-a-number/assets/147473334/7e55089b-7514-48d3-ad57-1720aa726d51)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
