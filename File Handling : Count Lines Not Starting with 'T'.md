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
def create_file(file_path,file_content):

    with open(file_path,'w') as file:

        file.write(file_content)
        
def count_words_in_file(file_path):
    
    with open(file_path,'r') as file:
    
        content=file.read()
        
        words=content.split()
        
        return len(words)

## Output
![IMG-20250902-WA0002 1](https://github.com/user-attachments/assets/6a61ceb4-4dc7-440c-be84-f91576d07a7b)

## Result
Thus, the Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T' is executed and verified successfully.
