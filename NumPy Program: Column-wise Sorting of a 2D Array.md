# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
arr = np.array([[9, 3, 5],
                [1, 8, 2],
                [4, 6, 7]])
print("Original Array:")
print(arr)
sorted_arr = np.sort(arr, axis=0)
print("\nArray after sorting each column:")
print(sorted_arr)
```
## Output
<img width="398" height="384" alt="image" src="https://github.com/user-attachments/assets/4fc4c0d0-4b98-4b15-a509-0471095952c4" />

## Result
Hence the python program is executed sucessfully.
