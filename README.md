# Customer Purchase Behavior Analysis 

## Project Overview
This project analyzes customer purchase behavior using **Python** to derive meaningful insights and provide data-driven business recommendations.  
The analysis helps in understanding **top-selling products, customer segmentation, sales trends, and customer retention strategies**.

## Objective
- Identify **high-value customers** for targeted engagement.
- Analyze **best-selling products** and revenue patterns.
- Detect **sales trends** to optimize marketing and inventory strategies.
- Develop **customer retention strategies** to minimize churn.

## Dataset
- The dataset contains **transactions from an e-commerce store**.
- It includes details like **Invoice No, Stock Code, Description, Quantity, Invoice Date, Price, Customer ID, and Country**.

## Steps Performed
### 1. Data Cleaning & Preprocessing  
- Removed missing values and duplicates.  
- Handled incorrect or negative entries in quantity and price.  
- Converted date columns to the correct format.

### 2. Exploratory Data Analysis (EDA)  
- Basic statistical summary of sales.  
- Identified **top-selling products** based on quantity.  
- Analyzed **total revenue by country**.  
- Examined **monthly sales trends** to identify seasonality.  
- Visualized **top 10 customers by revenue** using a bar chart.  
- Analyzed **sales distribution by weekdays**.  

### 3. Customer Segmentation (RFM Analysis)  
- **Recency**: Days since the last purchase.  
- **Frequency**: Number of purchases.  
- **Monetary**: Total amount spent.  
- Segmented customers into **Champions, Loyal Customers, Lost Customers, Potential Loyalists, and At Risk**.

### 4. Business Insights & Recommendations  
**4.1 Customer Segmentation Insights & Recommendations**  
- Majority of customers are **Lost Customers (3,643)**.  
- Only **534 Champions** who make frequent, high-value purchases.  
- **Retention strategies** suggested for re-engagement.

**4.2 Sales & Revenue Trends Insights & Recommendations**  
- **United Kingdom** contributes the highest revenue.  
- **Best-selling products** identified for inventory optimization.  
- Recommendations made for **sales improvement strategies**.

**4.3 Product Purchase Behavior Insights & Recommendations**  
- **Top-selling products** identified by quantity sold.  
- Slow-moving items bundled with popular ones to improve sales.  

**4.4 Customer Retention & Churn Reduction Insights & Recommendations**  
- High churn rate observed, leading to strategies like **personalized marketing and loyalty programs**.  

## Business Impact  
- **Revenue Concentration** – A small percentage of customers (Champions & Loyal Customers) contribute a significant portion of revenue.  
- **Sales Trends** – Sales are highest on certain weekdays (e.g., Thursdays) and lowest on others (e.g., Sundays).  
- **Top-Selling Products** – Products like *Paper Craft* and *Storage Jars* drive high sales volume.  
- **Customer Churn Risk** – A large number of customers fall into the "Lost Customers" category, requiring re-engagement strategies.  
- **Geographical Revenue Distribution** – The **UK** is the highest revenue-generating country.  

## 🛠 Tools Used  
- **Python (Pandas, Matplotlib, Seaborn, Plotly, Scikit-learn)**  
- **Jupyter Notebook**  

## 📂 Dataset  
The dataset used for this analysis is available on Kaggle: [Dataset Link](<INSERT_KAGGLE_LINK_HERE>)  

