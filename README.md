## How to use 

1. Export all your trade history 

2. Load the .ipynb into your jupyter notebook 

3. Change the value of FILE_PATH in row 2 your file name 

4. Run notebook Kernel and cells 

5. Populate the ticker you want to display under by changing the value of TICKER. 

**Drop empty columns**

`df.drop(df.columns[df.columns.str.contains('unnamed',case = False)],axis = 1, inplace = True)`

## Extra resources

[Breaking Up A String Into Columns Using Regex In pandas](https://chrisalbon.com/python/data_wrangling/pandas_regex_to_create_columns/)

[Creating a Waterfall Chart in Python](https://pbpython.com/waterfall-chart.html)