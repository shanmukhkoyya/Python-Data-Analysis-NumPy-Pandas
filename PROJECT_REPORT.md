# Project Report: NumPy and Pandas Practice

## Project purpose

This project works through the first Python data analysis assignment using two small examples: daily temperature readings and a table of transactions. The aim is to practise basic data handling and explain what each operation returns.

## Data used

### Temperature readings

The notebook uses seven daily average temperatures for each of two weeks. The values are supplied directly in the assignment; they are not collected from a weather service.

### Transactions

The transaction table has 10 rows and four fields:

| Field | Meaning |
|---|---|
| `TransactionID` | Identifier for a transaction |
| `ProductCategory` | Product group |
| `Region` | Sales region label |
| `Amount` | Transaction amount; the currency is not specified in the assignment |

These are small, assignment-provided example values, not a real company dataset.

## Work completed

- Built 1D and 2D NumPy arrays and inspected their shape, data type, and size.
- Converted Celsius values to Fahrenheit and calculated maximum, minimum, and mean temperature.
- Practised array slicing to select days and weeks.
- Created a Pandas Series with custom labels, selected values with `.loc` and `.iloc`, filtered marks, updated an entry, removed an entry, and divided the remaining marks by 10 for the assignment's CGPA exercise.
- Inspected a DataFrame, selected columns, filtered records, counted categories, identified unique regions, and grouped the original data to calculate mean amount.
- Updated transaction 102, calculated a temporary 10% Discount column, removed transaction 109, and then removed the Discount column.

## Findings from the original transaction table

These figures are calculated before the assignment's data-modification steps.

- **Category counts:** Electronics — 4; Clothing — 3; Furniture — 3.
- **Mean amount by region:** East — 375.00; North — 287.50; South — 250.00; West — 190.00.
- **North-region records with Amount greater than 200:** TransactionIDs 103, 106, and 110.
- **Temperature summary for Week 1:** minimum 20.8°C, maximum 26.1°C, and mean approximately 23.54°C.

The category counts and regional means describe the supplied sample only. They should not be interpreted as business-wide performance measures.

## Final state after the manipulation exercise

The requested operations are applied in this order: change TransactionID 102's amount from 150 to 165, create a 10% Discount column, remove TransactionID 109, and delete the temporary Discount column. The final table contains **9 rows and 4 columns**, with TransactionID 109 absent and TransactionID 102's Amount set to 165.

## Limitations and next steps

- The examples are small and manually supplied, so they do not represent a full business dataset.
- No currency, time period, profit, cost, or customer information is provided; this project does not make claims about profit or commercial performance.
- The CGPA calculation follows the assignment's requested arithmetic and is not intended as an official academic conversion rule.
- A useful next project would use a larger dataset and a clearly stated business question, then document data cleaning, analysis, visualisation, and recommendations.

## Run the notebook

Install the packages listed in [requirements.txt](requirements.txt), start Jupyter Notebook, and run `python_data_analysis_numpy_pandas.ipynb` from top to bottom.
