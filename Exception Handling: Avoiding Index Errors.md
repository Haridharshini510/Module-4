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
```
n=int(input())
l=[] 
for i in range(n):
    l.append(int(input()))
x=int(input())
try:
   
    print(l)
    print(l[x])
        
except:
    print(f"{x} is not accepted")

```
## Output
<img width="718" height="441" alt="image" src="https://github.com/user-attachments/assets/23f03f25-7413-420d-8419-50e079dadc5a" />

## Result
Thus, the program was executed successfully and the IndexError was handled using exception handling.
