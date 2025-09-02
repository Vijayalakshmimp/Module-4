# Exception Handling in Python: Prevent the program from crashing

## 🎯 Aim
To write a Python program that demonstrates exception handling by attempting to call a non-existent list method (.get()) and using the pass keyword in the except block to prevent the program from crashing.

## 🧠 Algorithm
1. Start the program.
2. Define a list a with some integer elements.
3. Use a try-except block:
   • In the try block, attempt to call the .get() method on the list a.
   • Since lists do not have a .get() method, an exception will be raised.
   • In the except block, use the pass keyword to handle the error silently.
4. Print the list a after the exception handling.
5. End the program.

## 🧾 Program
a = [1, 3, 5]

try:

    a.get()

except:

    pass

print(a)

## Output
<img width="1159" height="246" alt="image" src="https://github.com/user-attachments/assets/ca151e70-aa65-4187-aba1-1dd47943caa5" />

## Result
Thus, the  Python program that demonstrates exception handling by attempting to call a non-existent list method (.get()) and using the pass keyword in the except block to prevent the program from crashing is executed and verified successfully.
