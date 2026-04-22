# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd
df1 = pd.DataFrame({
    'Name': ['Alice', 'Bob'],
    'Age': [23, 25]
})
df2 = pd.DataFrame({
    'Name': ['Charlie', 'David'],
    'Age': [22, 24]
})
print("DataFrame 1:")
print(df1)
print("\nDataFrame 2:")
print(df2)
df_new = pd.concat([df1, df2], axis=0)
print("\nConcatenated DataFrame:")
print(df_new)
```

## Output
<img width="406" height="555" alt="image" src="https://github.com/user-attachments/assets/5480c3fd-f984-4215-9d2c-6303e47565f7" />

## Result
Hence the python program is executed sucessfully.
