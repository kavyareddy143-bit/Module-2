## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
real=int(input())

imag=int(input())

c=complex(real,imag)

print(c)

print(c.real)

print(c.imag)

## Output
<img width="387" height="301" alt="image" src="https://github.com/user-attachments/assets/0bbf6f88-29c4-488e-9b34-25f7e2920d28" />

## Result
The program was executed successfully
