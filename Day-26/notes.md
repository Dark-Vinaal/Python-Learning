## 🗓️ Day-26 — NumPy & Pandas Libraries

### 🎯 Topics Covered

- What `NumPy` is (basic array usage)
- What `Pandas` is (DataFrame usage)
- Reading/Writing Excel & CSV files
- Working with arrays and basic functions

---

## NumPy (Numerical Python)

### NumPy is a powerful library used for:

- Numerical computations
- Working with arrays
- Performing mathematical operations faster

### To use NumPy:
```python
import numpy as np
```

---

## 1. Creating an Array
```python
import numpy as np

arr = np.array([1, 2, 3, 4])
print(arr)
```

---

## 2. Checking Length of Array
```python
import numpy as np

arr = np.array([10, 20, 30])
print(len(arr))   # Output: 3
```

---

## Pandas Library

### Pandas is used for:

- Handling structured data
- Creating and modifying DataFrames
- Reading/writing Excel and CSV files

### Importing Pandas:
```python
import pandas as pd
```

---

## 1. Creating a DataFrame
```python
import pandas as pd

data = {
    "Name": ["John", "Liya", "Karan"],
    "Age": [22, 24, 21]
}

df = pd.DataFrame(data)
print(df)
```

---

## 2. Export DataFrame to Excel — to_excel()
```python
df.to_excel("students.xlsx", index=False)
```

---

## 3. Read Excel File — read_excel()
```python
df = pd.read_excel("students.xlsx")
print(df)
```

---

## 4. Export DataFrame to CSV — to_csv()
```python
df.to_csv("students.csv", index=False)
```

---

## 5. Read CSV File — read_csv()
```python
df = pd.read_csv("students.csv")
print(df)
```

---

## 📘 *Next step (Day 27):*  

I’ll explore **OOPS**.