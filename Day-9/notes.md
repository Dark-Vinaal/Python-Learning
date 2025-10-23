# 🗓️ Day 9 — Python Input Method & f-Strings

## 🎯 Topics Covered
- `input()` method  
- Printing user input  
- Using variables inside strings with **f-strings**

---

## 💬 The `input()` Function

The `input()` function is used to take **user input** from the console.

### 🧠 Syntax:
```python
variable_name = input("Enter something: ")
name = input("Enter your name: ")
print("Hello,", name)
```

### 🧾 Explanation:

- input() pauses program execution and waits for user input.
- Whatever the user types is always taken as a string by default.

---

## ⚙️ Printing input() Directly

You can also take input and print it immediately without storing it in a variable.

### 🧩 Example:
```python
print(input("Enter your favorite color: "))
```

### 🧾 Explanation:

- The input() function runs first (asks for input).
- The print() function then displays whatever the user entered.

---

## ✨ f-Strings in Python

f-strings (formatted string literals) allow embedding variables inside strings using {}.

### 🧠 Syntax:
```python
f"string with {variable}"
```

### 💻 Example:
```python
name = input("Enter your name: ")
age = input("Enter your age: ")
print(f"Hello {name}, you are {age} years old!")
```

### 🧾 Explanation:

- Prefix the string with f to enable variable interpolation.
- Variables inside {} are automatically replaced with their values.

---

## 🧠 Summary

| Concept          | Description                          | Example                         |
| ---------------- | ------------------------------------ | ------------------------------- |
| `input()`        | Takes user input (string by default) | `input("Enter name: ")`         |
| `print(input())` | Prints user input directly           | `print(input("Enter value: "))` |
| `f-strings`      | Used to embed variables in strings   | `f"Hello {name}"`               |

---

📘 *Next step (Day 10):*  

I’ll explore **Operators**.