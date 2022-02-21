# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```

Program to find the gcd of two number using function.
Developed by: bhuvaneshwari.s
RegisterNumber:  21500835

def gcd():
    if x > y:
        smaller = y
    else:
        smaller = x
    for i in range(1, smaller+1):
        if((x % i == 0) and (y % i == 0)):
            gcd = i 
    return gcd

x = int(input())
y = int(input())

print("GCD of two numbers is:", gcd())



## Output:

![Screenshot (20)](https://user-images.githubusercontent.com/94828604/154975528-b4df30c2-243b-404a-9149-bc5e03e0fef6.png)





## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
