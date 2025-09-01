# File Handling in Python: Print Lines Containing a Specific Substring

## 🎯 Aim
To write a Python program that reads a text file and prints all lines that contain a specific substring.

## 🧠 Algorithm
1. Define a function `create_file(file_path, content)` to create a file with the given content:

   * Open the file in **write mode**.
   * Write the `content` to the file.
   * Close the file automatically using a `with` statement.
2. Define a function `print_lines_with_substring(file_path, substring)` to print lines containing a specific substring:

   * Open the file in **read mode**.
   * Iterate through each line in the file:

     * Check if the `substring` exists in the current line.
     * If yes, print the line after removing any leading/trailing whitespace using `.strip()`.
   * Close the file automatically using a `with` statement.
3. Call the functions with appropriate `file_path`, `content`, and `substring` to see the results.

## 🧾 Program
```
# Function to create a file with specified content
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

# Function to print lines that contain a specific substring
def print_lines_with_substring(file_path, substring):
    with open(file_path, 'r') as file:
        for line in file:
            if substring in line:
                print(line.strip())
```
## Output
<img width="1282" height="251" alt="image" src="https://github.com/user-attachments/assets/22ff3318-b764-4328-ae34-21aa3b8b0e7d" />

## Result
The program successfully reads a text file and prints all lines that contain the specified substring.
