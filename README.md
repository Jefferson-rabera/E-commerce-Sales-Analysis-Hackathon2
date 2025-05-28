# E-commerce-Sales-Analysis-Hackathon2
The Data Analysis Hackathon which focuses on the E-commerce sales insight. 
Project by: Jefferson Rabera Mogoi

## Overview of the project
Analysing the E-commerce sales data with the use of Excel, SQL, Python and Power BI to uncover trends and insights for customers.

## The structure of the repository
1. `SQL_Queries.sql`: SQL data cleaning and analysis.
2. `Python_Scripts.ipynb`: Python scripts for EDA and visualization.
3. `PowerBI_Dashboard.pbix`: Power BI dashboard file.

## Dataset source.
The source of the dataset is: [Kaggle E-commerce Sales Dataset](https://github.com/jefftizo/E-commerce-Sales-Analysis-Hackathon)

## Data cleaning process using Excel.
1. I started by performing data cleaning using excel.
   The cleaning process entailled removing duplicate data. It appeared that there was no duplicated data or figures in the dataset.
2. The dataset had columns, Region, Age which was identified as blank cells which had to be recftified. The rectification entailed the use of filter function to check the blank cells and replace them using the replace function where for region, I had to replace the cells with unknwon and the column Age to be replaced with 0.

3. In the process of data cleaning also, the column Unit price had some cells with decimal digits whereas most of the figures was integers. To maintain consistency, I rounded off the figurs to integers using the `Round` function.

## 
