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
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
~~~
dict1=eval(input())
sort_dict=sorted(dict1.keys())
print("Keys and Values sorted in alphabetical order by the key")
for x in sort_dict:
   print(F"{(x,dict1[x])}",end=' ')
~~~

## Output

<img width="1260" height="295" alt="image" src="https://github.com/user-attachments/assets/a0748a5b-ce42-4ecc-a261-3765f1b00070" />

## Result
Thus, the program has been verified successfully.
