## Task 1: Build a small DataFrame by hand

| household_id | household_size | monthly_kwh | housing_type    | income_bracket |
| ------------ | -------------- | ----------- | --------------- | -------------- |
| 101          | 4              | 420.5       | Apartment       | Lower-Middle   |
| 102          | 6              | 610.0       | Villa           | High           |
| 103          | 3              | 300.2       | Apartment       | Low            |
| 104          | 5              | 505.8       | Detached House  | Upper-Middle   |
| 105          | 2              | 210.4       | Courtyard House | Low            |
| 106          | 7              | 690.3       | Villa           | High           |

- **(a)** Create a DataFrame called `task_1_df` containing this table.
- **(b)** Display the first 5 rows, the shape, the data types, and the `info()` summary.
- **(c)** Which pandas data type did each column receive? Does `household_id` deserve to be treated as a number in calculations?

---

## Task 2: Use the attached dataframe

Use the attached DataFrame `df` (from the CSV file).

- **(a)** Display the first 7 rows, the shape, the column names, and a random sample of 20 rows.
- **(b)** Use `info()` and `dtypes`. Are all columns the type you expected?

---

# The submission guidelines

- **YOU MUST** push the homework file to a separated branch called `homework_1_<Student-FirstName_SecondName_ThirdName>` like `homework_1_Ali_Jasem_Muhammed`.
- Submit **one** `.ipynb` file named `HW_1_<Student-FirstName_SecondName_ThirdName>.ipynb` like `HW_1_Ali_Jasem_Muhammed.ipynb` with **all cells executed - each code block executed in a separate cell** (outputs visible).
- Every written answer must be in a **Markdown cell** placed directly under the corresponding task.
- Similar notebooks will receive zero.