# NumPy & Pandas — Practical Data Lab

**Notebook:** python_data_analysis_numpy_pandas.ipynb  
**Level:** Introductory Python data analysis  
**Focus:** Array operations, labelled data, filtering and grouped summaries

## Lab map

| Exercise | Data used | Practice |
|---|---|---|
| NumPy arrays | Daily temperature readings | 1D/2D arrays, shape, type, size, slicing and Celsius-to-Fahrenheit conversion |
| Pandas Series | Student marks | Labels vs positions, .loc, .iloc, Boolean filtering and a CGPA exercise |
| Pandas DataFrame | Small transaction table | Column selection, filtering, category counts, unique regions and regional mean amount |

The transaction exercise also updates TransactionID 102, calculates a temporary discount, removes TransactionID 109, and then removes the discount column.

## Selected checks from the original examples

These values refer to the original transaction table before the modification exercise.

| Check | Result |
|---|---:|
| Week 1 average temperature | 23.54°C |
| Week 1 temperature range | 20.8°C–26.1°C |
| Electronics transactions | 4 |
| Clothing transactions | 3 |
| Furniture transactions | 3 |
| Highest regional mean amount | East — 375 |
| Lowest regional mean amount | West — 190 |

The examples are small assignment datasets. They are practice checks, not evidence of wider business trends. The currency for transaction amounts is not specified.

## Files in this repository

- [Notebook](python_data_analysis_numpy_pandas.ipynb) — code and saved outputs.
- [Project report](PROJECT_REPORT.md) — method, results, final table state and limitations.
- [Requirements](requirements.txt) — Python package list used by the notebook.
- [Assignment PDF](Python%20DA%20Assignment%201%20-%20Data%20Analysis%20using%20NumPy%20and%20Pandas.pdf) — original task instructions.

## Reproduce the lab

Install packages listed in requirements.txt, start Jupyter Notebook, open python_data_analysis_numpy_pandas.ipynb and run the cells from top to bottom.

## Skills practised

**NumPy:** array construction, inspection, conversion, aggregation and slicing.

**Pandas:** Series labels, index-based access, Boolean masks, DataFrame selection, row updates, row removal, category counts, unique values and group means.

## Reflection

The main learning point is the difference between a label and a position in a Pandas Series, and how the same table can be explored through column selection, filters and grouped calculations. The next step after these small exercises is to apply the same operations to a larger dataset with a defined analysis question.

---

[GitHub profile](https://github.com/shanmukhkoyya) · [LinkedIn](https://www.linkedin.com/in/shanmukh-koyya/) · [Email](mailto:shanmukhkoyya1234@gmail.com)
