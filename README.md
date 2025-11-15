# 📊 Restaurant Data Exploration Project (Python + SQLite)

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
It reveals seasonality, trends, and data completeness.

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

<img width="370" height="675" alt="image" src="https://github.com/user-attachments/assets/e91ce44e-1e48-43ab-9ecb-e0658cc0271e" />


#### 2. Find the total number of items on the menu

Insight:
Shows menu breadth and complexity.

<img width="88" height="74" alt="image" src="https://github.com/user-attachments/assets/7755f4ff-96e1-4a45-881e-e4eb1aea5ba1" />


#### 3. Identify the least and most expensive items

Insight:
Reveals price extremes and helps understand menu pricing strategy.

<img width="287" height="70" alt="image" src="https://github.com/user-attachments/assets/ecc4f812-27b9-48f4-8015-1f7bcb3bac13" />

<img width="311" height="76" alt="image" src="https://github.com/user-attachments/assets/8c9624b1-7416-4443-96af-b61668489577" />



#### 4. Count how many Italian dishes are in the menu

Insight:
Highlights cuisine representation and category balance.

<img width="363" height="308" alt="image" src="https://github.com/user-attachments/assets/ba4ee185-8d13-44e9-b3de-ac20088d1ce5" />

<img width="86" height="63" alt="image" src="https://github.com/user-attachments/assets/5fb166fb-2d77-4f14-bea3-b13b854f9586" />


#### 5. Identify the least and most expensive Italian dishes

Insight:
Provides detail into pricing distribution within a specific cuisine.

<img width="300" height="64" alt="image" src="https://github.com/user-attachments/assets/3ea15825-a820-4cf1-9d55-045eca7b8142" />

<img width="321" height="66" alt="image" src="https://github.com/user-attachments/assets/6024ea39-f271-4873-8378-b4a8b40ec537" />


#### 6. Count how many dishes exist in each category

Insight:
Shows how balanced or skewed the menu is across food types.

<img width="206" height="168" alt="image" src="https://github.com/user-attachments/assets/79a65f0b-fe1c-46cb-b030-f9d86cc3e87e" />


#### 7. Compute the average dish price per category

Insight:
Helps analyze pricing tiers and evaluate whether certain categories are underpriced or overpriced.

<img width="187" height="169" alt="image" src="https://github.com/user-attachments/assets/9f563a7b-1742-4c7b-b8ef-afa2913d259a" />


### Menu_orders_items.ipynb

Combined analysis from joining order_details and menu_items.

#### 1. Merge order and menu data into one table

Insight:
Joining both tables enables richer insights—such as spending, popularity, or category trends.

<img width="738" height="633" alt="image" src="https://github.com/user-attachments/assets/6cc16ea3-9dee-4829-9e9a-d1e748c39cbb" />


#### 2. Identify least and most ordered items + their categories

Insight:
Shows customer preferences, unpopular dishes, and category demand—useful for optimizing the menu.

Includes:

**Least ordered item**

<img width="267" height="63" alt="image" src="https://github.com/user-attachments/assets/d930627e-cbda-4280-ad21-0cd875a565a4" />


**Most ordered item**

<img width="267" height="66" alt="image" src="https://github.com/user-attachments/assets/c9ec036b-e6ac-41cd-9aef-cf4d171940b4" />


**Combined output**

<img width="277" height="98" alt="image" src="https://github.com/user-attachments/assets/04f6be5c-72a9-4dd6-b892-ad3617665a48" />


#### 3. Identify the top 5 highest-spend orders

Insight:
Helps uncover big-ticket transactions, ideal for targeted marketing or operational planning.

<img width="344" height="224" alt="image" src="https://github.com/user-attachments/assets/75d2ffcb-2f60-46c8-b270-d63b2ab8b017" />


#### 4. View and analyze the highest-spend order

<img width="156" height="162" alt="image" src="https://github.com/user-attachments/assets/285f0e2b-ec36-4328-a282-d0274ff8297d" />

<img width="172" height="160" alt="image" src="https://github.com/user-attachments/assets/4c033a57-424c-4d8f-b8e2-2314b8ed198e" />

<img width="232" height="639" alt="image" src="https://github.com/user-attachments/assets/2b73a473-3af6-47a3-88f9-b1677da6ca8c" />


### 🧰 Tools Used

- Python (Pandas, SQLite3, Jupyter)
- SQLite
- Jupyter Notebook
