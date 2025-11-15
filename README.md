# 📊 Data Exploration Project (Python + SQLite)

### This project explores restaurant data using Python, SQLite, and Jupyter Notebook. It includes data cleaning, joining tables, and extracting insights from menu and order information.


The analysis is organized into three notebooks:

- Orders_details.ipynb
- Menu_items.ipynb
- Menu_orders_items.ipynb (combined dataset analysis)


**Orders_details.ipynb**

Analysis of the order details dataset.

#### 1. View the order_details table

Why this matters:
Understanding the raw structure helps verify the fields, detect missing data, and plan the exploration.

<img width="502" height="429" alt="image" src="https://github.com/user-attachments/assets/c5fcb8b1-a6c6-4c11-bbd5-cff3ba2d01a9" />


#### 2. Identify the date range of the table

Insight:
The timeframe determines how representative the data is. It reveals seasonality, trends, and data completeness.

#### 3. Count how many orders were made within this date range

Insight:
Provides an overview of customer activity and restaurant performance during the observed period.

#### 4. Count how many items were ordered within this date range

Insight:
Helps measure total operational load and overall demand.

#### 5. Identify which orders had the most items

Insight:
Large orders often indicate group purchases, catering events, or unusual spikes in activity.

#### 6. Count how many orders had more than 12 items

Insight:
Useful for detecting bulk orders—important for staffing, inventory planning, or ordering patterns.

