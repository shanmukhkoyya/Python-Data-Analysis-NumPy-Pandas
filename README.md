# Python Data Analysis with NumPy and Pandas

This is my first Python data analysis assignment. I used two small examples—a set of daily temperatures and a transaction table—to practise the NumPy and Pandas operations I am learning.

## What is in the notebook?

**NumPy — temperature readings**
- Create 1D and 2D arrays and inspect their shape, type, and size.
- Convert Celsius to Fahrenheit and calculate the minimum, maximum, and average.
- Select days and weeks with array slicing.

**Pandas — student marks**
- Work with a Series that uses rank labels.
- Practise `.loc`, `.iloc`, Boolean filtering, updating a value, removing a label, and dividing marks by 10 for the assignment's CGPA exercise.

**Pandas — transaction table**
- Inspect the table and select columns.
- Filter transactions, count product categories, find unique regions, and calculate mean amount by region.
- Apply the requested edits: update TransactionID 102, calculate a temporary discount, remove TransactionID 109, and remove the discount column.

## A few results

These results come from the original transaction table, before the modification exercise.

| Check | Result |
|---|---|
| Week 1 average temperature | 23.54°C (approximately) |
| Week 1 temperature range | 20.8°C to 26.1°C |
| Electronics transactions | 4 |
| Clothing transactions | 3 |
| Furniture transactions | 3 |
| Highest regional mean amount | East — 375 |
| Lowest regional mean amount | West — 190 |

The sample is small, so these are checks of the assignment data—not evidence of wider business trends. The amount's currency is not specified.

## Project files

- [Jupyter notebook](python_data_analysis_numpy_pandas.ipynb) — code and saved outputs.
- [Project report](PROJECT_REPORT.md) — method, results, final table state, and limitations.
- [Requirements](requirements.txt) — packages used by the notebook.
- [Original assignment PDF](Python%20DA%20Assignment%201%20-%20Data%20Analysis%20using%20NumPy%20and%20Pandas.pdf) — task instructions.

## Run it on your computer

From the project folder, run:

```bash
python -m pip install -r requirements.txt
jupyter notebook
```

Open `python_data_analysis_numpy_pandas.ipynb` and run the cells from top to bottom.

## What I learned

This exercise gave me practice with array operations, Series labels and positions, conditional filtering, grouping, and modifying a DataFrame. My next step is to apply these techniques to a larger dataset with a clear analysis question.
