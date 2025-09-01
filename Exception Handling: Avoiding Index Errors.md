# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Take an integer input n from the user representing the number of elements in the list.
2. Initialize an empty list a.
3. Use a for loop that runs n times:

   Take an integer input elem from the user.
   Append elem to the list a.

4. Print the complete list a.
5. Use a try-except block to access the 7th element (a[6]):

   In the try block, attempt to print a[6].
   In the except IndexError block, print the message "6 is not accepted" if the index is out of range.

## 🧾 Program
```
n = int(input())
a = []

for i in range(n):
    elem = int(input())
    a.append(elem)
    
print(a)

try:
    print(a[6])
except IndexError:
    print("6 is not accepted")
```
## Output
<img width="758" height="319" alt="image" src="https://github.com/user-attachments/assets/e0ee0c97-e2ce-4ac8-8f65-97ac49683355" />

## Result
The program successfully creates a list from user inputs and handles attempts to access an index that may not exist.
