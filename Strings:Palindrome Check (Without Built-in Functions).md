# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
string = "google"

is_palindrome = True

for i in range(len(string) // 2):
    if string[i] != string[len(string) - i - 1]:
        is_palindrome = False
        break
if is_palindrome:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
## Output
<img width="377" height="190" alt="image" src="https://github.com/user-attachments/assets/440a116f-141a-4a61-81cf-bbed1598aa28" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
