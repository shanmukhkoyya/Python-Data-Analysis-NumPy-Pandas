# Python Data Analysis with NumPy and Pandas

This repository contains my work for **Python DA Assignment 1**. I used a small set of temperature values and a transaction table to practise the NumPy and Pandas operations covered in the assignment.

## What I worked on

### NumPy
- Created one-dimensional and two-dimensional temperature arrays.
- Checked array shape, data type, and number of elements.
- Converted Celsius values to Fahrenheit and calculated minimum, maximum, and mean temperatures.
- Selected values using array slicing.

### Pandas Series
- Created a Series with custom rank labels.
- Used `.loc`, `.iloc`, and a Boolean condition to retrieve values.
- Updated a mark, removed an entry, and divided the remaining marks by 10 for the assignment's CGPA exercise.

### Pandas DataFrame
- Explored rows, columns, shape, and data types.
- Selected columns and filtered transactions using conditions.
- Counted product categories, listed unique regions, and calculated average transaction amounts by region.
- Updated TransactionID 102, calculated a temporary 10% Discount column, removed TransactionID 109, and deleted the Discount column as required.

## Files

- **`python_data_analysis_numpy_pandas.ipynb`** — notebook with the code and saved outputs.
- **`Python DA Assignment 1 - Data Analysis using NumPy and Pandas.pdf`** — assignment brief used for this exercise.
- **`requirements.txt`** — Python packages needed to run the notebook.

## Run it locally

Use Python 3, then install the packages:

```bash
python -m pip install -r requirements.txt
jupyter notebook
```

Open `python_data_analysis_numpy_pandas.ipynb` and run the cells from top to bottom.

## Final checks

The notebook finishes by checking that the NumPy arrays have shapes `(7,)` and `(2, 7)`, the updated marks Series contains Rank1 through Rank4, and the final transaction table has 9 rows and 4 columns.

This is a learning assignment with small, explicitly defined examples; the goal is to show the operations and their results clearly.

## A few results from the notebook

- Week 1's average temperature is about **23.54°C**; the lowest value is **20.8°C** and the highest is **26.1°C**.
- The original transaction table contains 4 Electronics, 3 Clothing, and 3 Furniture records.
- Before the data-modification exercise, the average transaction amount by region is East **375**, North **287.5**, South **250**, and West **190**.
- The final table contains **9 rows and 4 columns**. The discount is calculated and then removed because that is the sequence required by the assignment.

The regional averages above are calculated before TransactionID 102 is changed from 150 to 165, matching the notebook's order of work.
