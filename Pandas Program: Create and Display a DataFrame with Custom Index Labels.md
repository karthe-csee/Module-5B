# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [23, 25, 22],
    'City': ['New York', 'London', 'Paris']
}
index_labels = ['A', 'B', 'C']
df = pd.DataFrame(data, index=index_labels)
print(df)
```

## Output
<img width="385" height="252" alt="image" src="https://github.com/user-attachments/assets/5de7dc63-af39-422e-927a-4d7c87a640f1" />

## Result
Hence the python program is executed sucessfully.
