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
~~~
def create_file(file_path,file_content):
   with open(file_path,'w') as file:
      file.write(file_content)
def count_words_in_file(file_path):
   with open(file_path,'r') as file:
      content=file.read()
      words=content.split()
      return len(words)
~~~
## Output

<img width="1227" height="207" alt="image" src="https://github.com/user-attachments/assets/451b5756-9357-4edc-9ac3-b9405ca28e68" />

## Result
Thus, the program has been executed successfully.
