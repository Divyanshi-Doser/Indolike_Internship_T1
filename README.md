# 🛍️ Customer Segmentation using RFM & KMeans

This project is part of my **internship Task 1** as a **Data Analysis at Indolike**.  
The goal was to segment retail customers based on their purchase behavior using **clustering techniques**, mainly **RFM analysis** and **KMeans**.

---

## 📁 Files Included

- 📄 `Customer_Segmentation.ipynb` – Full analysis notebook with code, charts & steps
- 📄 `Customer_Segmentation.pdf` – Final cleaned PDF report
- 📊 `Customer_Segments.csv` – Output file with final segmented customers
- 📈 `RFM Averages By Cluster.png` – Bar chart of RFM metrics per cluster
- 📈 `Recency Distribution.png` – Distribution plot of Recency scores
- 📈 `Frequency Distribution.png` – Distribution plot of Frequency scores
- 📈 `Monetary Distribution.png` – Distribution plot of Monetary scores
- 📊 `Customer Count Per Cluster.png` – Count of customers in each cluster

---

## 🧠 Project Objective

> **Perform customer segmentation** on a retail dataset using K-Means clustering,  
> based on RFM (Recency, Frequency, Monetary) values to group customers into meaningful segments.

---

## 🔍 Key Steps Performed

1. Loaded and merged retail data from 2 years
2. Removed duplicates and cleaned missing values
3. Filtered out negative quantity and price
4. Created `TotalSales` and calculated RFM scores
5. Scaled data using `StandardScaler`
6. Applied **KMeans (k=3)** clustering on RFM scores
7. Analyzed clusters with charts and generated insights

---

## 📊 Cluster Summary (k = 3)

| Cluster | Customers | Behavior |
|---------|-----------|----------|
| 0       | 2001      | Low activity – may be inactive |
| 1       | 3855      | Moderate buyers – casual and re-engageable |
| 2       | 22        | VIP – frequent, recent, high-spending |

---

## 💡 Key Insights

- **Cluster 1** has most of the customers with moderate activity — they can be retained with regular engagement.
- **Cluster 0** is less active and might include churned customers.
- **Cluster 2** is a small but valuable segment — recent, loyal and high spenders.

---

## 📬 Recommendations

- 🎯 **Cluster 2**: Send loyalty rewards and early-access offers.
- 🔁 **Cluster 1**: Share regular email campaigns or discounts.
- 💤 **Cluster 0**: Reactivate with targeted win-back messages or coupons.

---

## 📌 Tools & Libraries Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (StandardScaler, KMeans)
- Jupyter Notebook

---

## 📍 Internship Info

**Project Title**: Customer Segmentation  
**Internship Task**: Task 1 – Data Analysis Role  
**Company**: indolike 

---

## 🔗 Author

**Divyanshi Doser**  
📧 [LinkedIn Profile](https://www.linkedin.com/in/divyanshi-doser/)  
💼 Aspiring Data Analyst

---

