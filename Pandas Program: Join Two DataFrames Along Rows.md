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

##💻 Program
```
import pandas as pd
student_data1 = pd.DataFrame({
    'student_id': [1, 2, 3],
    'name': ['Alice', 'Bob', 'Charlie'],
    'age': [20, 21, 22]
})
student_data2 = pd.DataFrame({
    'student_id': [4, 5, 6],
    'name': ['David', 'Eve', 'Frank'],
    'age': [23, 24, 25]
})
combined_data = pd.concat([student_data1, student_data2], axis=0)
print(combined_data)
```
## Output
<img width="1532" height="1001" alt="Screenshot 2025-10-19 094123" src="https://github.com/user-attachments/assets/c1390464-c02b-4e43-8b6b-75fb6e31f23d" />

## Result
The Pandas Program: Join Two DataFrames Along Rows is executed successfully.
