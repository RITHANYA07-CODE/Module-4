# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the sorted dictionary.
6. **End the program.**

---

## 🧪Program
```
my_dict = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}
sorted_items = sorted(my_dict.items(), key = lambda x : x[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)
```
## Sample Output
<img width="1177" height="157" alt="image" src="https://github.com/user-attachments/assets/dc916fd5-836a-4562-a247-9a9a30f0d1ea" />

## Result
The program successfully sorts the dictionary items by their values in ascending order.
