# Basic-Excel-Functions 
# Introduction
As part of assessment in the Data Analytics class organized by PSP Analytics, one of the analytics projects I’ll be working on is the Basic Excel Functions on Bike Buyers Dataset.The Basic Excel Functions on Bike buyers dataset contains the Customer ID,	Customer Name,	Marital Status,	Gender,	Income,	Children,	Education,	Occupation and other data of the Basic Excel Function. The goal of this work is to analyze the Basic Excel Functions, their uses and to uncover insights to be used for the business growth.

# Data Sourcing
This dataset used in this work is gotten from the Data Analytics Class announcement channel, which was posted by Mr. Kingsley Adisa.

# Data Preparation
I will load the dataset into  MS Excel workbook.

# Data Cleaning/Transformation
Here, I check if the format of each column is correct and correct it were necessary. I also address inconsistencies in the columns to ensure a more accurate dataset for analysis

Now, I format the Income, column to display currency

# Data Exploration/Visualization
1. Aggregate Functions: You are required to use aggregate functions to perform calculations on the 
`Income` column of the dataset. For each task, insert a new column as needed and perform the 
following:
  a. Use the `SUM` function to calculate the total income from all customers.

  ![SUM](https://github.com/user-attachments/assets/8c63a2d2-eed7-4e31-bed8-df7e3907b7a7)

  b. Use the `AVERAGE` function to find the average income of customers.

  ![AV](https://github.com/user-attachments/assets/eb6f4bf7-19de-4ff7-b3fb-10aa75f50bd7)

  c. Use the `MAX` function to identify the maximum income.

  ![image](https://github.com/user-attachments/assets/0d57e8d3-7976-4dbf-9d90-99e49f9280ba)

  d. Use the `MIN` function to find the minimum income.
  
  ![image](https://github.com/user-attachments/assets/15cc2189-0b03-40d9-9e72-db0839886bae)

  e. Use the `COUNT` function to count how many income values are available (non-blank).

  ![image](https://github.com/user-attachments/assets/d4e5585e-5ba0-433e-9640-4fe41be2f7cf)

3. Text Functions: Use text functions to manipulate data in the Customer Name and Customer ID
columns.
  a. Use the `LEFT` function to extract the first 2 characters from the Customer ID column.
  b. Use the `RIGHT` function to extract the last 3 characters of the Customer Name column.
  c. Use the `LEN` function to find the length of each name in the Customer Name column.

  ![image](https://github.com/user-attachments/assets/c6b6ebd7-67a5-4724-99bf-8e7f80ee940f)

  d. Use the `CONCAT` function (or `TEXTJOIN` if preferred) to combine the Customer Name and Customer ID into a single column with the format "Customer Name – Customer ID"

  ![image](https://github.com/user-attachments/assets/66e81a80-643a-4dad-98b2-b3522bc040c1)

  e. Use the `TRIM` function to remove any leading or trailing spaces in the Customer Name column.

  ![image](https://github.com/user-attachments/assets/03167747-a2b8-46ef-8906-fb95177c3b32)

  
5. Logical Functions: Use logical functions to analyze and perform conditional operations based on 
  the data.
  a. Use the `IF` function to create a new column labeled "High Income", where customers with an income above $50,000 are marked as “Yes” and those below are marked as “No.”

  ![image](https://github.com/user-attachments/assets/25d40c16-998b-461c-b606-9ed67a420b99)

  b. Use the `SUMIF` function to calculate the total Income for customers who are married (i.e M).

  ![image](https://github.com/user-attachments/assets/d8985622-e4e6-4498-84d4-becd49627bb0)

  c. Use the `COUNTIF` function to count how many customers have an income greater than $50,000.

  ![image](https://github.com/user-attachments/assets/ab455dde-3f2d-4c8c-b862-0537f83924a2)

  d. In a new column named “Age Bracket”, Use the `IFS` function to classify customers age into categories:- Adolescents (0-30), - Middle age (31-54), and - Old (55+)

  ![image](https://github.com/user-attachments/assets/0dee2cee-cd69-482b-859c-ff8993c92603)

  e. Use the `AND` function to create a new column that checks if a customer’s income is greater than $50,000 and their age is greater than 30

  ![image](https://github.com/user-attachments/assets/65bdc4c1-2a9e-4d6b-8a0c-0a4e1e5202c4)


Conclusion
So far, I’ve been able to load, clean and perform some of the excel basic functions using the Basic Excel Functions dataset on Bike buyers and to draw valuable insights through the business questions. Based on these findings, i can be able to provide data-driven recommendations to help for business growth. a display of the dataset and the work done on it is displayed below.

1. Original dataset 

  ![20250204_155125](https://github.com/user-attachments/assets/607c4384-9e4c-4f27-8c8b-ded089efe667)

2. Cleaned Dataset

   ![20250204_155218](https://github.com/user-attachments/assets/c0f3ad66-150b-4201-bf5d-b595fec49f37)


