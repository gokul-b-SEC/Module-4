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
Add Code here
```
a={2:56,1:2,5:12,4:24,6:18,3:323}
b=sorted(a.items(),key=lambda x:x[1])
print(f"Keys and Values sorted in alphabetical order by the value\n{b}")
```

## Sample Output
<img width="1102" height="158" alt="image" src="https://github.com/user-attachments/assets/68efdf57-c67a-40f8-8a3f-330d2fa6b507" />


## Result

