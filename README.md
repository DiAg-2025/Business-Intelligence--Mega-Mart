# Mega Mart

[Dataset](https://github.com/DiAg-2025/Business-Intelligence--Mega-Mart/blob/main/csv_dataset.zip)

Objectives:
1. Calculate the total sales value of the Mega Mart. Also, find the total discount value and the overall percentage discount given by the Mega Mart.
2. Calculate the total quantity sold. Find the maximum quantity sold in a single row and inspect it as well. Does this row have a high discount percentage?
3. Find the total sales value per basket and the total sales value per household. Plot the distribution of total sales value purchased at the household level.
4. What are the top 10 households by quantity purchased and the top 10 households by sales value? Plot the total sales value for the top 10 households by value, ordered from highest to lowest.
5. Which products have the most sales by sales value? Plot a horizontal bar graph. Did the top 10 selling items have a higher-than-average discount rate?
6. What was the most common product among those with the households in the top 10 households by sales value?
7. Look up the product ID that had the highest quantity sold in a single row.
8. Plot the sum of sales by month. Are the sales growing over time? Now plot the same series after filtering down to dates between April 2016 and October 2017.
9. Plot the sum of monthly sales in 2016 vs the monthly sales in 2017.
10. Plot the total sales by day of the week.
11. Plot the sum of sales by age and the sum of sales by income.
12. Calculate the mean household sales by age and household composition. Which of the demographics has the highest average sales?
13. Calculate the sum of sales by age and department. Which category does the youngest demographic perform well in? Export the pivot table in an Excel file.

![Python](https://img.shields.io/badge/Py_libraries-pandas,_pumpy,_matplotlib,_seaborn,_openpyxl-lightgreen)

[Analysis](https://github.com/DiAg-2025/Business-Intelligence--Mega-Mart/blob/main/JupyterAnalysis.ipynb)

Findings:
1. Total sales = 6666244.5, total discount value = 1184679.8, and overall percentage discount = 17.77.
2. The total quantity sold is 216713611, the maximum quantity sold in a single row is 89638, and no, it does not have a high discount percentage.
3. Total sales value per basket = 28.61798, and total sales value per household = 3175.914. Most of the households have a sales value under 5000.
4. The top household by quantity purchased is 1023, and the top household by sales value is 1023. 8 of the top 10 households by value have a sales value of around 20000.
5. 6534178 product ID has the most sales by sales value. 7 of the top 10 products do not have a higher-than-average discount rate.
6. 6533889 product ID is the most common product.
7. 6534178 product ID has the highest quantity sold, which is 89638.
8. Yes, sales are growing over time. The data is available up to 11 December 2017, so there is a sudden drop that is not very insightful, hence filtered out.
9. On average, the sales in 2017 are more than the sales in 2016.
10. The majority of sales are in the first half of the week.
11. People aged 45-54 and people with an income of around 50000-74000 contributed the most to sales.
12. Demographics where age is 55-64 and household composition is unknown have the highest average sales.
13. The youngest demographic performs best in GROCERY. [Exported Excel file](https://github.com/DiAg-2025/Business-Intelligence--Mega-Mart/blob/main/exported_excel_sheet.xlsx)


 
