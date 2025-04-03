# Row Mean Exercise

This notebook demonstrates basic NumPy operations with 2D arrays, including conditional replacement, row-wise computations, and exporting results.

## Task Description

1. Create a NumPy array of shape **(6, 6)** with **random integers between 1 and 50**.
2. Replace all values that are **divisible by 3** with `0`.
3. Calculate the **mean of each row** and store the values in a separate array.
4. Add the row means as a **new column** to the original array.
5. Save the resulting array as `matrix_with_means.csv`.

## Skills Practiced

- Filtering values using boolean masks (`array % 3 == 0`)
- Row-wise aggregation with `np.mean(..., axis=1)`
- Adding new columns using `np.column_stack()`
- Saving arrays to CSV using `np.savetxt()`

## 📁 Files

- `row_mean_exercise.ipynb` – Jupyter notebook with code and explanations

