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

import numpy as np

x = np.array([3, 5, 2, 7, 1])

y = np.array([1, 6, 2, 5, 3])

indices = np.where(x >= y)[0]  

print("Array x:", x)

print("Array y:", y)

print("\nIndices where x >= y:", indices)

## Output

![Screenshot 2025-04-30 163416](https://github.com/user-attachments/assets/9af1d784-8b55-4185-a218-45acefc2284d)


## Result

This program is successfully executed.
