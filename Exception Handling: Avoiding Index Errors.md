# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```py

msg = [5, 10, 20]
try: print(msg[5])
except IndexError: print("You're out of list range")
```
## Output

<img width="610" height="166" alt="444871889-2a1b39ba-09c1-4a4e-b219-bce320f4ab72" src="https://github.com/user-attachments/assets/bdef827f-f110-427b-8e2f-90c45370e380" />

## Result
Thus,the program has been executed successfully.
