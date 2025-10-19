# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np  
x = np.array([10, 5, 8, 3, 15])
y = np.array([7, 5, 10, 2, 15])
greater = x > y
equal = x == y
print("x > y :", greater)
print("x == y :", equal)
indices = np.where(x >= y)
print("Indices where x >= y:", indices)
print("Values of x where x >= y:", x[indices])

```

## Output
<img width="1902" height="802" alt="Screenshot 2025-10-19 095218" src="https://github.com/user-attachments/assets/56392c35-e3fe-4831-ac91-a2686754c382" />

## Result
The NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y is executed successfully.
