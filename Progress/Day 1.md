# Day 1
---------------------

### **Question 1:**

> ***Take a list and print out all the elements of the list that are less than a number, defined by user (i.e. 5)***

```python
num = int(input("Please enter a number: "))

a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
b = []
```

> **My Solution:**
```python
for item in a:
    if item < num: b.append(item)

print(b)
```

> **Suggested Solution:**
```python
print([item for item in a if item < num])
```
---------------------