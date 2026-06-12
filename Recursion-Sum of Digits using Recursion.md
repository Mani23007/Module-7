# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
```python
def sum_digit(n):
    if n <= 0:
        return 0
    return n % 10 + sum_digit(n // 10)

n = int(input("Enter a number: "))
result = sum_digit(n)

print("Sum of digits =", result)
```

## OUTPUT:
<img width="476" height="180" alt="image" src="https://github.com/user-attachments/assets/8e68173b-49aa-4f04-8cf0-82043e85f444" />


## RESULT:
Thus,the program is executed successfully.
