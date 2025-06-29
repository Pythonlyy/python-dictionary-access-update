# 🔁 Access & Update Dictionary Values in Python

Learn how to retrieve and modify data inside a Python dictionary using keys.

---

## 💡 What You'll Learn

* How to access existing values by key
* How to update a value in a dictionary
* How to add a new key-value pair
* How to check if a key exists before using it

---

## 💻 Example with Explanation

### 🗂️ Start with a dictionary:

```python
user = {"name": "Alice", "age": 30}
```

### 🔍 Access a value:

```python
user = {"name": "Alice", "age": 30}
print(user["age"])
```

🖨️ Output:

```
30
```

### ✏️ Update a value:

```python
user = {"name": "Alice", "age": 30}
user["age"] = 31
print(user["age"])
```

🖨️ Output:

```
31
```

### ➕ Add a new key-value pair:

```python
user = {"name": "Alice", "age": 31}
user["location"] = "Berlin"
print(user["location"])
```

🖨️ Output:

```
Berlin
```

---

## 📌 Key Notes

* Use `dict[key]` to access or update a value
* If the key doesn’t exist, it will be created
* Existing values are overwritten silently

---

## 🧪 Try It Yourself

```python
car = {"brand": "Tesla", "year": 2020}
car["year"] = 2024
car["model"] = "Model 3"
print(car)
```

### 🔈 Expected Output

```
{'brand': 'Tesla', 'year': 2024, 'model': 'Model 3'}
```

---

💡 **Quick Tip:** Check if a key exists before accessing it:

```python
user = {"name": "Alice", "age": 31, "location": "Berlin"}

if "location" in user:
    print("Yes, location is set!")
```

🖨️ Output:

```
Yes, location is set!
```

---

🐍 This is part of the **Pythonly** beginner series.
Learn Python one line at a time. Follow **[@Pythonly](https://www.youtube.com/@Pythonly)** for more.

---

