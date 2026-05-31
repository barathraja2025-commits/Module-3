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
```


import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = []
for item in items:
    if not re.search(r'e', item):
        result.append(item)
print(result)



```
## Output




<img width="918" height="199" alt="530708069-05567430-21d8-457b-9661-0780abf41bb3" src="https://github.com/user-attachments/assets/3468c8b8-540c-457f-a5bb-5c42470c220a" />

## Result
