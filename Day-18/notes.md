# 🗓️ Day 18 — String Methods in Python

---

## 🎯 Topics Covered
- `upper()`
- `lower()`
- `title()`
- `capitalize()`
- `swapcase()`
- `join()`
- `split()`

---

## 🧩 1. `upper()` — Convert to Uppercase

- Converts all characters in a string to **uppercase** letters.

```python
text = "python is fun"
print(text.upper())
```

### 🧠 Output:
```python
PYTHON IS FUN
```

---

## 🧩 2. lower() — Convert to Lowercase

- Converts all characters in a string to lowercase letters.

```python
text = "HELLO WORLD"
print(text.lower())
```

### 🧠 Output:
```python
hello world
```

---

## 🧩 3. title() — Convert to Title Case

- Capitalizes the first letter of every word.

```python
text = "dark ai is learning python"
print(text.title())
```

### 🧠 Output:
```python
Dark Ai Is Learning Python
```

---

## 🧩 4. capitalize() — Capitalize First Word Only

- Converts the first character of the string to uppercase and the rest to lowercase.

```python
text = "welcome to python programming"
print(text.capitalize())
```

### 🧠 Output:
```python
Welcome to python programming
```

---

### 🧩 5. swapcase() — Swap Upper and Lowercase

- Converts uppercase letters to lowercase and vice versa.

```python
text = "PyThOn Is AwEsOmE"
print(text.swapcase())
```

### 🧠 Output:
```python
pYtHoN iS aWeSoMe
```

---

## 🧩 6. split() — Split String into List

- Splits a string into a list based on a separator (default is space " ").

```python
text = "Python is fun"
print(text.split())
```

### 🧠 Output:
```python
['Python', 'is', 'fun']
```

> You can also specify a separator:

```python
data = "apple,banana,cherry"
print(data.split(","))
```

### 🧠 Output:
```python
['apple', 'banana', 'cherry']
```

---

## 🧩 7. join() — Join Elements of List into String

- Joins list elements into a single string with a specified separator.

```python
fruits = ['apple', 'banana', 'cherry']
print(", ".join(fruits))
```

### 🧠 Output:
```python
apple, banana, cherry
```

---

## 🔹 Summary Table

| Method         | Description                           | Example                        | Output          |
| -------------- | ------------------------------------- | ------------------------------ | --------------- |
| `upper()`      | Converts all letters to uppercase     | `"hello".upper()`              | HELLO           |
| `lower()`      | Converts all letters to lowercase     | `"HELLO".lower()`              | hello           |
| `title()`      | Capitalizes first letter of each word | `"dark ai".title()`            | Dark Ai         |
| `capitalize()` | Capitalizes only first word           | `"python is fun".capitalize()` | Python is fun   |
| `swapcase()`   | Swaps case of letters                 | `"PyThOn".swapcase()`          | pYtHoN          |
| `split()`      | Splits string into list               | `"a,b,c".split(",")`           | ['a', 'b', 'c'] |
| `join()`       | Joins list into string                | `"-".join(['a','b','c'])`      | a-b-c           |

---


## 📘 *Next step (Day 19):*  

I’ll explore **Set**.