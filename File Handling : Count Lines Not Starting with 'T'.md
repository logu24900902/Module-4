# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def find_and_replace(file_path, old_word, new_word):
    with open(file_path,'r')as f:
        cr=f.read()
        l=cr.replace(old_word,new_word)
    with open(file_path,'w') as f:
        f.write(l)


def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()
```

## Output
<img width="566" height="416" alt="image" src="https://github.com/user-attachments/assets/7d8650b7-d0e5-4d73-a65a-dceaef0d5d42" />

## Result
Thus the program executed successfully.
