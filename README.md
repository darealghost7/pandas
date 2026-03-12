
Pandas Series and DataFrame Basics
This Jupyter notebook demonstrates fundamental pandas operations for data manipulation.

Overview
The notebook covers:

Creating pandas Series from lists and dictionaries

Basic Series operations (max, sum)

Index manipulation and updates

Converting between Series and DataFrames

Import/Export operations (CSV, Excel)

Key Operations
Series Creation
python
# From list
my_series = pd.Series([10, 20, 30, 40, 50])

# From dictionary with custom index
population = {"California": 395382223, "Texas": 29145505}
pope_series = pd.Series(population)
Data I/O
Save to CSV: .to_csv("filename.csv")

Save to Excel: .to_excel("filename.xlsx")

Read from CSV: pd.read_csv("filename.csv")

Read from Excel: pd.read_excel("filename.xlsx")

Files Generated
Pope.csv - Population data exported to CSV

Pope.xlsx - Same data exported to Excel format

Requirements
pandas

