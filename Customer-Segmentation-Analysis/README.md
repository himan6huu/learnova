# Customer Segmentation Analysis

## Project Overview
This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) analysis and K-Means Clustering. The objective is to group customers based on purchasing behavior to help businesses improve marketing strategies, customer retention, and decision-making.

---

## Problem Statement
The aim of this project is to analyze customer transaction data and segment customers into different groups based on their purchasing patterns. By identifying valuable and inactive customers, businesses can create targeted marketing campaigns and improve customer engagement.

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset Information
The dataset contains online retail transaction details including:
- Invoice Number
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## Project Workflow

### 1. Data Loading
- Imported dataset using Pandas
- Explored dataset structure

### 2. Data Cleaning
- Checked missing values
- Removed duplicates
- Converted invoice dates

### 3. Feature Engineering
Created:
- Total Amount column
- RFM metrics:
  - Recency
  - Frequency
  - Monetary Value

### 4. Data Scaling
- Standardized RFM values using StandardScaler

### 5. Customer Segmentation
- Applied Elbow Method
- Implemented K-Means Clustering

### 6. Visualization
- Customer segmentation scatter plot
- Elbow method graph

---

## Key Insights
- High-value customers were identified based on purchase frequency and spending behavior.
- Some customer groups showed low engagement and lower spending patterns.
- Businesses can use these segments for personalized marketing strategies.

---

## Recommendations
- Provide loyalty rewards to high-value customers.
- Target inactive customers with promotional campaigns.
- Improve customer retention strategies using segmentation insights.

---

## Conclusion
This project successfully implemented customer segmentation using RFM analysis and K-Means clustering techniques. The analysis provides valuable business insights that can help organizations improve customer targeting and business performance.

---

## Project Files
- Customer_Segmentation_Analysis.ipynb
- customer_segments.png
- elbow_method.png
- README.md

---

## Author
Himanshu Kumar
