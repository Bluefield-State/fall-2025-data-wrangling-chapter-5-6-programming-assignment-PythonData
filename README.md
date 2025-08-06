# Chapter 5-6 Programming Assignment

## Problem Statement

You are tasked with analyzing sales data from a CSV file named `sales_data.csv`. The file contains the following columns:

- `product`: Name of the product sold.
- `quantity`: Number of units sold.
- `sale_price`: Price per unit.
- `date`: Date of the sale (format: YYYY-MM-DD).

Your tasks are to use pandas to:

1. Read the sales data from the CSV file.
2. Calculate the total sales for each product.
3. Calculate the average sale price for each product.
4. Identify the product with the highest total sales.
5. Calculate the correlation and covariance between `quantity` and `sale_price`.
6. Create a summary report that includes:
   - Total sales for each product.
   - Average sale price for each product.
   - The product with the highest sales.
   - Correlation and covariance between `quantity` and `sale_price`.
7. Write the summary report to a new CSV file named `sales_summary.csv`.

## Expected Output

After running the notebook, you should see output similar to this:

```
Sales Summary Report:
             Total Sales  Average Sale Price Highest Sales Product  Highest Sales Value  Correlation (Quantity, Sale Price)  Covariance (Quantity, Sale Price)
product                                                                              
Widget A        42.50                  2.50               Widget B                65.00                                0.75                               7.50
Widget B        65.00                  5.00               Widget B                65.00                                0.75                               7.50
Widget C        21.00                  7.00               Widget B                65.00                                0.75                               7.50

Summary report written to 'sales_summary.csv'
```