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
keys = input()
values = input()
keys_list = eval(keys)
values_list = eval(values)
result = dict(zip(keys_list, values_list))
print(result)
```

## Output
<img width="1200" height="341" alt="image" src="https://github.com/user-attachments/assets/76489b0d-e835-4e35-9178-582205d2071b" />

## Result
Thus the program executed successfully.
