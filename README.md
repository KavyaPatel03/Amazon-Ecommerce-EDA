# Amazon-Ecommerce-EDA
As a part of an E-Commerce Retail Marketplace, which specialises in selling a wide variety of consumer and wholesale products across multiple countries, we need to identify the operational and behavioral patterns that influence order value, customer spend, and purchasing cycles. When managing an online marketplace, platforms face critical decision-making challenges around inventory allocation, pricing, and campaign scheduling. This decisioning is associated with two key risks:

a. If customer demand peaks at specific hours or within certain countries and the platform fails to target or stock inventory accordingly, it results in missed revenue and lost market share;  
b. If the platform misinterprets extreme outlier orders (such as rare bulk or B2B orders) as typical consumer behavior, marketing spend and inventory forecasts will be allocated inefficiently, leading to financial loss and supply chain imbalance.

The dataset contains transaction-level information from past sales, including product details, unit prices, quantities purchased, customer locations, and order timestamps. We need to perform Exploratory Data Analysis (EDA) to understand how geographical attributes and temporal attributes (day of the week, hour of the day) influence purchasing behavior. In other words, the company wants to understand the driving factors behind high-value transactions and customer spending habits. The company can utilize this knowledge for ad-campaign scheduling, logistics optimization, and revenue growth.

# Objective
The objective is to analyze transaction patterns, optimize marketing schedules, and separate baseline consumer trends from extreme purchasing spikes, enabling maximized revenue and improved operational efficiency. This case study aims to achieve this goal through exploratory data analysis (EDA) using the provided dataset.

The company wants to understand the driving factors (or driver variables) behind order value variations across different hours, weekdays, and global markets. The company can utilize this knowledge for inventory positioning, flash-sale planning, and customer segmentation.

The primary objective of this exercise is to assist the e-commerce business in optimizing marketing and fulfillment operations. This challenge arises from two potential scenarios:

1. Identifying peak purchasing hours and days with high recurring demand is crucial, as targeted advertising and flash promotions during these windows can significantly boost conversion and profit. Neglecting these windows results in underutilized marketing budgets.
2. On the other hand, failing to detect and handle extreme purchasing anomalies (outliers) can distort overall retail metrics, leading to flawed revenue forecasting and mismatched stock planning across warehouses.

# Steps Of EDA
- **1. Data Understanding**
- **2. Data Cleaning**
- **3. Feature Engineering & Preprocessing**
- **4. Data Analysis**
- **5. Data Visualisation**

# Technologies Used
- **Pandas**
- **Numpy**
- **Matplotlib**
- **Seaborn**

# Steps to do the EDA
- **Analyze the meaning of data and perform feature engineering (extracting `hour`, `day_name`, and calculating `amount_spent = quantity * unit_price`)**
- **Clean the data according to the need (handling missing values, cancellations, and irregular records) and handle extreme outliers statistically**
- **Do the EDA by answering business questions**
- **Visualize the results into graphs and charts using matplotlib and seaborn**

# Key Findings of the EDA
- **Early-Morning Surge:** A sharp escalation in average order values occurs at 7:00 AM from Wednesday through Friday, indicating recurring commercial or bulk replenishment orders.
- **Mid-Week Workday Consistency:** Tuesdays exhibit the steadiest purchasing power across business hours (8:00 AM – 4:00 PM), peaking mid-morning.
- **Afternoon & Weekend Slump:** Spending drops during early afternoons (12:00 PM – 2:00 PM) and late evenings. Saturday transactions reflect lower-ticket individual consumer purchases, while Sundays record zero operational activity.
- **High-Ticket Outlier Influence:** Extreme order amounts heavily skew linear distributions and color scales unless properly normalized using percentile limits.

# Limitation of the EDA
- **Limited to single-metric aggregations**

# Author
Kavya Patel
