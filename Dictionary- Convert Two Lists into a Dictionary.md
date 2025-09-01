## Dictionary Operations in Python: Convert Two Lists into a Dictionary

## 🎯 Aim
To write a Python program that converts two lists into a dictionary, using items from the first list as keys and items from the second list as values.

## 🧠 Algorithm
1. Define two lists: keys for dictionary keys and values for corresponding values.
2. Initialize a dictionary using a dictionary comprehension:
   For each index i, set keys[i] as the key and values[i] as the value.
3. Print the resulting dictionary.

## 🧾 Program
```
keys = eval(input())
values = eval(input())
result = dict(zip(keys, values))
print(result)
```
## Output
<img width="1128" height="246" alt="image" src="https://github.com/user-attachments/assets/670a5962-87ae-4ab5-a823-83722bdd7d0a" />

## Result
The program successfully converts two lists into a dictionary, mapping each key from the first list to its corresponding value from the second list.
