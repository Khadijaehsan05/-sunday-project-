# Sunday Project - Data Quality, Insights and CSV Operations

GitHub repository: https://github.com/Khadijaehsan05/sunday-project

## What this project does

Part A: I loaded sales_raw.csv, cleaned it, added a revenue column,
made a summary by region and by category, and made two charts.
Part B: I loaded cleaned_sales.csv, added a tax column, increased
the price of Books by 10%, removed one row, and saved sales_updated.csv.

## Files

- sunday_project.ipynb - the notebook with Part A and Part B
- sales_raw.csv - the input file, not changed
- cleaned_sales.csv - the cleaned data from Part A, 13 rows
- sales_updated.csv - the edited data from Part B, 12 rows
- revenue_by_region.png - chart 1
- revenue_by_category.png - chart 2
- README.md - this file

## How to run the notebook

1. Put all the files in the same folder. In Google Colab, upload
   sunday_project.ipynb and sales_raw.csv to the same folder.
2. Open sunday_project.ipynb.
3. Run all the cells from top to bottom.
4. The notebook makes cleaned_sales.csv, sales_updated.csv and
   the two chart files in the same folder.

I used Python 3 with pandas and matplotlib only.

## Results

- Rows before cleaning: 21. Rows after cleaning: 13.
- I removed 1 duplicate row and 7 rows with missing, wrong or
  out of range values. The price 10000 was treated as a wrong price.
- Total revenue after cleaning: 3775.
- Revenue by region: North 1470, South 1035, East 740, West 530.
- Revenue by category: Food 1945, Books 1370, Stationery 460.
- In Part B, Books prices went up by 10%, and I removed
  transaction_id 1001. Total revenue in sales_updated.csv is 3672.
