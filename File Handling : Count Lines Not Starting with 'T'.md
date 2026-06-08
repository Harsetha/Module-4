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
        if line.strip() and not line.lstrip().startswith('T'):
            count += 1
print("Sum :", count)
```

## Output

<img width="712" height="286" alt="568242555-5fed6921-1a9b-4dcd-a7bd-7c3ca8d5416a" src="https://github.com/user-attachments/assets/64b078b2-2549-45d0-8e0b-0b3d16e982f3" />

## Result
Thus, the program to merge two files into a third file using File Handling in Python was executed successfully
