## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
dict1=eval(input())
dict2=eval(input())
dict2.update(dict1)
print(dict2)
```

## Output
<img width="710" height="230" alt="image" src="https://github.com/user-attachments/assets/a8c76d8a-79bd-472d-929c-1e92ce83de6f" />

## Result
Thus, the program was executed successfully and two dictionaries were merged using the unpacking operator.
