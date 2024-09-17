# athletic_sales_analysis
Module 5 Challenge - Athletic Sales Analysis Challenge

# Project Overview
This module challenge focused on analyzing data to gain insights into which cities in the U.S. sold the most athletic wear over a two-year period, which retailers had the greatest total sales for athletic wear, which retailers sold the most women's athletic footwear, and which day and week had the highest sales for women's athletic footwear. 

**_Combining and Cleaning the Data_**:To complete this challenge, I imported two CSV files, athletic_sales_2020.csv and athletic_sales_2021.csv and read them into the DataFrames.

**_Analyzing the Data_**: After the CSV files were imported, I conducted data analysis to confirm that the two DataFrames had similar names and data types. I subsequently combined the two DataFrames by the rows using an inner join and I reset the index. After combining the DataFrames, I checked for any null values, checked each column's data type, converted the "invoice_date" colume to a datetime data type, and confirmed that the data type had been changed correctly. I then conducted data analysis utilizing the groupby and pivot_table functions.

**_Confirming the Work_**: To ensure that the athletic sales data analysis program ran as intended, I used both the groupby and pivot_table functions. I subsequently checked the results against each other and the sample output tables provided in the Module 5 Challenge instructions to confirm the output matched the expected outcomes.

# Programming Language
I used Python programming language to create the code for this project in Visual Studio Code.

# Resources 
I attended a tutoring session and received assistance with correcting the groupby coding to ensure that the data pulled correctly. I also received assistance with locating the proper naming convention for the women's athletic shoe sales. In addition, I referred to the class lecture files for additional support.
