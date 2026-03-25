# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
def remove(s, n):
    a = ""  # Initialize empty string
    
    # Iterate over each index
    for i in range(len(s)):
        if i != n:  # Skip the given index
            a += s[i]
    
    return a

# Read input string and index
string = input("Enter a string: ")
n = int(input("Enter index to remove: "))

# Call the function and print result
result = remove(string, n)
print("Modified string:", result)

## Output
<img width="385" height="218" alt="image" src="https://github.com/user-attachments/assets/1db1ae6b-d289-4c5c-87d8-19bafa9362be" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
