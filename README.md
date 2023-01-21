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
Developed by: 22002294
RegisterNumber: MOHANSIH K
def gcd():
    a=int(input())
    b=int(input())
    if(a<b):
        smaller=a
    else:
        smaller=b
    for i in range(1,smaller+1):
        if a%i==0 and b%i==0:
            gcd=i
    print("GCD of two numbers is:",gcd)
```

## Output:
![GCD OF THE NUMBER](https://user-images.githubusercontent.com/111619160/213843902-a77d4044-1f91-43a9-887e-ace505c6ed10.png)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
