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
```py

d = eval(input())
print("Keys and Values sorted in alphabetical order by the key")
for k in sorted(d): 
    print((k, d[k]), end=" ")
```
## Output

<img width="1069" height="124" alt="444871369-f5a989db-e61f-4a6b-8867-e1fb7dd3a5e6" src="https://github.com/user-attachments/assets/e6b90722-42a6-42aa-8d79-9a3529d879aa" />

## Result
Thus,the program has been executed successfully.
