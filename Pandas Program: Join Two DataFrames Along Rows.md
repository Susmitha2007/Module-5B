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

import pandas as pd

student_data1 = pd.DataFrame({
  
    'StudentID': ['S101', 'S102', 'S103'],
    
    'Name': ['Alice', 'Bob', 'Charlie'],
    
    'Age': [20, 21, 19]
    
})

student_data2 = pd.DataFrame({
  
    'StudentID': ['S104', 'S105'],
    
    'Name': ['David', 'Eva'],
    
    'Age': [22, 20]
    
})

combined_data = pd.concat([student_data1, student_data2], axis=0)

print("First DataFrame:")

print(student_data1)

print("\nSecond DataFrame:")

print(student_data2)

print("\nCombined DataFrame:")

print(combined_data)

print("\nCombined DataFrame Info:")

print(combined_data.info())

## Output

![Screenshot 2025-04-30 165047](https://github.com/user-attachments/assets/544ceb48-316a-482e-afd1-ac5ea8112af4)


## Result

This program is successfully executed.
