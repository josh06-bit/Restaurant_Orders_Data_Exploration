# 📊 Data Exploration Project (Python + SQLite)

### This project explores restaurant data using Python, SQLite, and Jupyter Notebook. It includes data cleaning, joining tables, and extracting insights from menu and order information.


The analysis is organized into three notebooks:

- Orders_details.ipynb
- Menu_items.ipynb
- Menu_orders_items.ipynb (combined dataset analysis)


### Orders_details.ipynb

Analysis of the order details dataset.

#### 1. View the order_details table

Why this matters:
Understanding the raw structure helps verify the fields, detect missing data, and plan the exploration.

<img width="502" height="429" alt="image" src="https://github.com/user-attachments/assets/c5fcb8b1-a6c6-4c11-bbd5-cff3ba2d01a9" />


#### 2. Identify the date range of the table

Insight:
The timeframe determines how representative the data is. It reveals seasonality, trends, and data completeness.

<img width="296" height="90" alt="image" src="https://github.com/user-attachments/assets/f5de58a9-a5fa-4546-9b84-4a41884adec3" />


#### 3. Count how many orders were made within this date range

Insight:
Provides an overview of customer activity and restaurant performance during the observed period.

<img width="250" height="83" alt="image" src="https://github.com/user-attachments/assets/ffac8b83-b709-4d82-b4fa-6171342e795e" />


#### 4. Count how many items were ordered within this date range

Insight:
Helps measure total operational load and overall demand.

<img width="103" height="81" alt="image" src="https://github.com/user-attachments/assets/94a27f66-fc25-4c5a-be0d-7660e116b035" />


#### 5. Identify which orders had the most items

Insight:
Large orders often indicate group purchases, catering events, or unusual spikes in activity.

<img width="158" height="641" alt="image" src="https://github.com/user-attachments/assets/84ab6629-d97f-46bf-bc2b-f2d03408596c" />



#### 6. Count how many orders had more than 12 items

Insight:
Useful for detecting bulk orders—important for staffing, inventory planning, or ordering patterns.

<img width="85" height="72" alt="image" src="https://github.com/user-attachments/assets/41fbf206-a855-44ad-8634-0535090aea91" />


### Menu_items.ipynb

Exploration of menu structure and pricing.

#### 1. View the menu_items table

Insight:
Gives an overview of the available dishes, categories, and prices.

#### 2. Find the total number of items on the menu

Insight:
Shows menu breadth and complexity.

#### 3. Identify the least and most expensive items

Insight:
Reveals price extremes and helps understand menu pricing strategy.

#### 4. Count how many Italian dishes are in the menu

Insight:
Highlights cuisine representation and category balance.

#### 5. Identify the least and most expensive Italian dishes

Insight:
Provides detail into pricing distribution within a specific cuisine.

#### 6. Count how many dishes exist in each category

Insight:
Shows how balanced or skewed the menu is across food types.

#### 7. Compute the average dish price per category

Insight:
Helps analyze pricing tiers and evaluate whether certain categories are underpriced or overpriced.
