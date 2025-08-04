Online Retail Customer Segmentation
 Project Overview
This project aims to analyze online retail customer behavior and segment customers based on their purchasing patterns. By understanding customer clusters, businesses can better target marketing efforts, tailor promotions, and improve customer retention strategies.

Dataset used: Online Retail II from the UCI Machine Learning Repository.

 Objectives
Clean and preprocess online transaction data
Engineer relevant features (e.g., Total Spending, Purchase Frequency)
Apply clustering techniques (KMeans + ensemble) to identify customer segments
Visualize patterns using Power BI for strategic business insights

 Methodology
Data Cleaning
Removed nulls, duplicates, and negative quantities
Filtered UK customers for consistency

Calculated new features like:
TotalSpending
PurchaseFrequency
Recency
Feature Engineering
Used RFM (Recency, Frequency, Monetary) model
Standardized features before clustering

Clustering

Applied KMeans algorithm (k=3 chosen based on elbow method)
Performed ensemble clustering for more stability
Labeled each customer with a Cluster (0, 1, or 2)
Visualization (Power BI)
Built an interactive dashboard showing:
Cluster distribution
Spending vs frequency
Segments over time
Customer drill-down

Results
Cluster 0 (Low Spend/Low Frequency)
Infrequent shoppers with low monetary value
Marketing Potential: New or lost customers
Cluster 1 (High Spend/High Frequency)
Most valuable and loyal customers
Ideal for loyalty programs and premium offers
Cluster 2 (Medium Spend/Medium Frequency)
Occasional buyers
Upsell/cross-sell opportunity group

 Recommendations
Focus retention campaigns on Cluster 1
Use incentives (coupons, discounts) to convert Cluster 2 into Cluster 1
Investigate causes of inactivity for Cluster 0 (e.g., churn reasons)

 Future Work
Include time-series analysis to forecast customer lifecycle
Test with DBSCAN or hierarchical clustering for comparison
Extend to multi-country customer base
Integrate with marketing automation tools

 Files in This Project
online-retail-customer-segmentation/
│
├── data/
│   ├── raw/                  # Original dataset
│   └── processed/            # Cleaned dataset
├── notebooks/
│   └── customer_segmentation.ipynb
├── powerbi/
│   └── customer_segmentation_dashboard.pbix
├── src/
│   ├── data_cleaning.py
│   ├── clustering.py
│   └── utils.py
├── visuals/
│   └── preview_dashboard.png
├── docs/
│   └── report.md             
├── requirements.txt
├── README.md

