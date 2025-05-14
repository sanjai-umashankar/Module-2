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
```
import math

def pascal_triangle(n):
    for i in range(n):
        for j in range(n - i - 1): 
            print(" ", end="")
        for j in range(i + 1):  
            print(math.comb(i, j), end=" ")
        print()

n = int(input("Enter the number of rows: "))
pascal_triangle(n)
```

## Sample Output
![image](https://github.com/user-attachments/assets/d64bc00b-6a48-490f-aa99-6b2b657378a8)
## Result
Thus the program has been successfully executed 
