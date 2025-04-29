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
a=int(input())
rev=0
tep=a
while a>0:
    b=a%10
    rev=(rev*10)+b
    a=a//10
if rev==tep:
        print(f"The given number {tep} is a Palindrome" )
else:
    print(f"The given number {tep} is not a palindrome" )
    
## Output
![WhatsApp Image 2025-04-29 at 22 09 01_3b0f37e0](https://github.com/user-attachments/assets/c1066e73-46d9-4bca-80d9-a1abe59834ca)

## Result
Thus the program excuted successfully.
