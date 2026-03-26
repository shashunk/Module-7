# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:
```
def fact(i):
   if i==1 or i==0:
       return 1
   else:
       return i*fact(i-1)
def sine(x,n):
  if n==0:
    return x
  else:
    return(((((-1)**n)*pow(x,(2*n+1)))/fact(2*n+1)))+sine(x,n-1)
x=int(input())
n=int(input())
print(sine(x,n))

```
## OUTPUT
![image](https://github.com/user-attachments/assets/32b898c1-c61f-40d2-8295-3226a7bfcf2a)

## RESULT
Program is successfully verified.
