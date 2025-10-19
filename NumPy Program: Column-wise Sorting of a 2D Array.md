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
arr=np.array(eval(input()))
s=np.sort(arr,axis=0)
print("Original Array:")
print(arr)
print("\nColumn-wise Sorted Array:")
print(s)
```
## Output
<img width="1740" height="697" alt="Screenshot 2025-10-19 093613" src="https://github.com/user-attachments/assets/af9457b6-9591-40e1-b61d-93b63e058e84" />

## Result
The NumPy Program: Column-wise Sorting of a 2D Array is executed successfully.
