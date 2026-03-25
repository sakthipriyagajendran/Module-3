# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result=[item for item in items if 'e' not in item]
print(result)
## Output
<img width="450" height="165" alt="image" src="https://github.com/user-attachments/assets/4ac215f0-a715-4353-9ab9-0410fc8fae25" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
