# Data Science Assignment: eCommerce Transactions Dataset

## Overview
This project focuses on analyzing an eCommerce Transactions dataset to extract business insights, build a lookalike model, and segment customers using clustering techniques.

## Files
- **Customers.csv**: Contains customer data (CustomerID, Name, Region, SignupDate).
- **Products.csv**: Contains product data (ProductID, Name, Category, Price).
- **Transactions.csv**: Contains transaction data (TransactionID, CustomerID, ProductID, Date, Quantity, TotalValue).

## Tasks

### Task 1: Exploratory Data Analysis (EDA)
Performed detailed EDA on:
- Revenue by region
- Top-selling products
- Monthly sales trends
- Revenue by product category
- Average transaction value by region
- Customer signup trends

### Task 2: Lookalike Model
Built a lookalike model to recommend similar customers based on transaction data using cosine similarity. A CSV file with the top 3 lookalikes for customers (C0001 - C0020) was generated.

### Task 3: Customer Segmentation
Applied KMeans clustering to segment customers based on transaction data and demographic features. Evaluated clustering quality using Davies-Bouldin Index and Silhouette Score.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

## Execution

To run the analysis:
1. Clone the repository:
   ```bash
   git clone https://github.com/Charan051/Zeotap_Assignment.git
2. Execute the notebooks for EDA, Lookalike Model, and Clustering.

## Deliverables
1. EDA Report (PDF)
2. EDA Code (Jupyter Notebook)
3. Lookalike Model Results (CSV)
4. Clustering Report (PDF)
5. Clustering Code (Jupyter Notebook)

## Conclusion

This project provides actionable insights into customer behavior, product performance, and segmentation strategies.
The lookalike model aids in targeted marketing, while clustering helps categorize customers for personalized strategies.
