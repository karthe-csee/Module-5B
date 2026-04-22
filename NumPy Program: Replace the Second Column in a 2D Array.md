# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy as np
arr = np.array([[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]])

print("Original Array:")
print(arr)
arr_deleted = np.delete(arr, 1, axis=1)
new_column = np.array([[10],
                       [20],
                       [30]])
arr_updated = np.insert(arr_deleted, 1, new_column, axis=1)
print("\nArray after deleting 2nd column and inserting new column:")
print(arr_updated)
```

## Output
<img width="621" height="368" alt="image" src="https://github.com/user-attachments/assets/ba812b3e-fa53-4aef-8745-dbd58642bb06" />

## Result
Hence the python program is executed sucessfully.
