# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
import math

def pascal_triangle(rows):
    for n in range(rows):
        print(" " * (rows - n - 1), end="")
        
        for k in range(n + 1):
            value = math.comb(n, k)
            print(value, end=" ")
        print() 
num_rows = int(input())
pascal_triangle(num_rows)

## Sample Output
![WhatsApp Image 2025-04-29 at 22 06 06_e78423e3](https://github.com/user-attachments/assets/1283c5d7-0c7e-40d8-b830-eefb457d2108)

## Result
Thus the program excuted successfully.

