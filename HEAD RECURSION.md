# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```python
def fun(n):
    if n > 0:
        fun(n - 2)
        print(n)

n = int(input("Enter a number: "))

if n % 2 != 0:
    n = n + 1

fun(n)
```
## OUTPUT:
<img width="504" height="261" alt="image" src="https://github.com/user-attachments/assets/0d2e80f0-4953-4df8-94db-08c0c6b1eebb" />


## RESULT:
Thus, the program is executed successfully.
