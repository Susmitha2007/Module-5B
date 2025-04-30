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

import pandas as pd

import numpy as np

exam_data = {
  
    'name': ['Alice', 'Bob', 'Charlie', 'David', 'Eva'],
    
    'score': [85, 92, 78, np.nan, 88],
    
    'attempts': [1, 3, 2, 3, 2],
    
    'qualify': ['yes', 'no', 'yes', 'no', 'yes']
    
}

labels = ['a', 'b', 'c', 'd', 'e']

df = pd.DataFrame(exam_data, index=labels)

print("Created DataFrame:")

print(df)

print("\nDataFrame info:")

print(df.info())

## Output

![Screenshot 2025-04-30 164724](https://github.com/user-attachments/assets/51d89b12-e9ad-4bc9-9161-327d247d9add)


## Result

This proram is successfully executed.
