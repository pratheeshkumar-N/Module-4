## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```py

dict1 = eval(input())
dict2 = eval(input())
merged_dict = {**dict1, **dict2}
print(merged_dict)
```
## Output

<img width="1132" height="250" alt="444864546-301c6dc7-6842-4151-94b0-27abc6e6c60d" src="https://github.com/user-attachments/assets/17434cbf-4264-4677-be7f-acb13347e393" />

## Result
Thus,the program has been executed successfully.
