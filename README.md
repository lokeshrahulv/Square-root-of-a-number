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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Lokesh Rahul V V 
RegisterNumber:  22004702
def my_method(num,num_iter =100):
    a=float(num)
    for i in range(num_iter):
        num=0.5*(num+a/num)
    return num    
     
a=int(input())
print("Square root of the number:",my_method(a))
*/
```

## Output:
![Screenshot (83)](https://user-images.githubusercontent.com/118423842/210347446-d093eca7-ce93-46a9-b669-4a008f6f99e6.png)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
