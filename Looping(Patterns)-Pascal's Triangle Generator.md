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
rows=int(input())

b=0

for i in range(rows,0,-1):

    b+=1
    
    for j in range(1,i+1):
    
        print(b,end=' ')
        
    print()

## Sample Output
<img width="435" height="481" alt="image" src="https://github.com/user-attachments/assets/d8e52b6c-45f6-4ff6-b2ef-1433ad366772" />

## Result
The program was executed successfully

