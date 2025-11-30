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
count = 0
with open("story.txt", "r") as file:
    for line in file:
        if not line.startswith('T'):
            count += 1
print("Number of lines not starting with 'T':", count)

```
## Output
<img width="982" height="112" alt="image" src="https://github.com/user-attachments/assets/f6cf7042-2205-4aaa-9129-985adff7d0e2" />

## Result
Thus, the program was executed successfully and the number of lines not starting with 'T' was counted from the file.
