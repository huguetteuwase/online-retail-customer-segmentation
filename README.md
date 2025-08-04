# 🛍️ Online Retail Customer Segmentation & Behavioral Analysis (2010–2011)

## 📌 Overview

This project explores how customers **shop online**, **when they buy**, **how much they spend**, and uses machine learning techniques to **segment customers** based on behavior. We use **Python (Jupyter Notebook)** for data analysis and **Power BI** for creating interactive dashboards to support business decision-making, customer targeting, and strategy optimization.

---

## 👤 Author

| Name                  | Student ID | Role         |
|-----------------------|------------|--------------|
| Teta Uwase Huguette  | 25513      | Data Analyst |

---

## 🎯 Project Objectives

- Identify customer purchase patterns: frequency, time of day, and spending habits  
- Segment customers using clustering algorithms  
- Create an interactive dashboard to communicate customer insights  
- Support eCommerce businesses in making data-driven decisions

---

## 🧰 Tools & Technologies

- 🐍 Python (Jupyter Notebook) – for preprocessing, EDA, clustering
- 📊 Power BI – for building interactive dashboards
- 📁 Excel / CSV – for storing and processing data
- 📦 scikit-learn – for clustering and evaluation
- 💾 GitHub – for version control and project collaboration

---

## 📥 Dataset Description

- **Source**: UCI Machine Learning Repository  
- **File**: `online_retail_II.xlsx`  
- **Timeframe**: 2010–2011  
- **Columns**:
  - `Invoice`, `StockCode`, `Description`, `Quantity`
  - `InvoiceDate`, `Price`, `Customer_ID`, `Country`
dataset link:https://archive.ics.uci.edu/ml/datasets/Online%20Retail%20II
---

## 🧼 Data Cleaning Steps

- Removed rows with missing or invalid values
- Filtered for positive `Quantity` and `Price`
- Converted `InvoiceDate` to datetime and extracted time features (hour, weekday)
- Created new features: `TotalAmount`, `PurchaseFrequency`, `TotalSpending`
- Exported cleaned dataset for further analysis and dashboard use

📂 **Output**: `cleaned_customer_data.csv`

---

## 📊 Exploratory Data Analysis (EDA)

Key steps and visuals include:

- Descriptive statistics of quantity, spending, and frequency  
- Hourly purchasing behavior (bar chart)  
- Top products and countries by sales  
- Weekday shopping patterns  

📷 **Sample Visuals**:
- Top 10 Countries by Sales  
- Most Purchased Products  
- Hour vs Purchase Frequency  

---

## 📈 Power BI Dashboard Highlights

Interactive dashboard summarizing key findings:

- 🧍 Cluster-wise segmentation of customers  
- 💵 Spending distribution and purchase patterns  
- ⏰ Time-of-day purchasing behavior  
- 🎯 Filters for cluster, weekday, and frequency range

📂 **Dashboard File**: `customer_segmentation_dashboard.pbix`

✅ Features:
- Slicers for cluster and purchase frequency
- Drill-down enabled bar and column charts
- Color-coded cluster visuals (Cluster 0 = Blue, 1 = Green, 2 = Red)

---

## 🧪 Machine Learning

- **Clustering Model**: `KMeans`  
- **Features Used**:
  - `TotalSpending`, `TotalQuantity`, `PurchaseFrequency`
- **Evaluation**:
  - Silhouette Score: ~`0.54`  
- **Innovation**:
  - Ensemble-style approach using simulated multiple clustering models for majority voting

---

## 📑 Key Insights

- 🧠 Cluster 0: Loyal, frequent buyers with moderate spending  
- 🛍️ Cluster 1: Infrequent but high-volume buyers  
- 💤 Cluster 2: Rare, high-spending anomalies  
- 🇬🇧 Most customers are from the United Kingdom  
- 🕖 Peak shopping time is between 10 AM and 2 PM

---

## 📦 Project Deliverables

| File                                     | Description                              |
|------------------------------------------|------------------------------------------|
| `customer_segmentation.ipynb`            | Full notebook with data pipeline         |
| `cleaned_customer_data.csv`              | Cleaned dataset                          |
| `customer_segmentation_dashboard.pbix`   | Interactive Power BI dashboard           |
| `preview_dashboard.png`                  | Dashboard screenshot                     |
| `requirements.txt`                       | Python dependencies                      |
| `README.md`                              | Project documentation                    |

---

## 🔮 Future Enhancements

- Add **RFM scoring** (Recency, Frequency, Monetary)  
- Integrate with **real-time data streams** (e.g., customer behavior logs)  
- Use **Deep Learning** for behavioral sequence modeling  
- Map users by region with **Power BI map visuals**  



<img width="692" height="347" alt="git" src="https://github.com/user-attachments/assets/2044baa0-0f13-426f-9b11-bc8caee545bf" />
<img width="501" height="344" alt="yeyeyeyeye" src="https://github.com/user-attachments/assets/7c8ba628-ca66-460f-9593-7b2d81d8ca43" />
<img width="534" height="289" alt="preview_dashboard" src="https://github.com/user-attachments/assets/d1a0dea6-bdd0-4f60-9f44-2a1d79de3e7f" />
