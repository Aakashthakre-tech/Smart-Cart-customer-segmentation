# 🛒 SmartCart Customer Clustering System

## 📌 Project Overview

SmartCart is a growing e-commerce platform serving customers across multiple countries. The company currently applies generic marketing strategies to all customers without understanding their behavioral differences.

This project builds an **Intelligent Customer Segmentation System** using **Unsupervised Machine Learning** to discover hidden patterns in customer behavior and group customers into meaningful clusters.

These clusters help businesses:
- Identify high-value customers
- Detect churn-prone users
- Improve marketing efficiency
- Enable personalized customer engagement

---

## 🎯 Problem Statement

SmartCart collected customer data containing **2240 customer records** and **22 attributes**, including:

- Demographics
- Purchase behavior
- Website activity
- Customer feedback

However, SmartCart currently lacks:

- Clear customer segmentation
- Targeted marketing strategies
- Efficient customer retention planning

To solve this, we develop a **Customer Clustering System** using **clustering algorithms** to segment customers based on their purchasing patterns and engagement levels.

---

## 📊 Dataset Description

Each row represents a **single customer**.

### 1️⃣ Customer Demographics

| Feature | Description |
|--------|-------------|
| ID | Unique customer identifier |
| Year_Birth | Year of birth |
| Education | Education level |
| Marital_Status | Marital status |
| Income | Yearly household income |
| Kidhome | Number of children |
| Teenhome | Number of teenagers |
| Dt_Customer | Date of enrollment |

---

### 2️⃣ Purchase Behaviour (Amount Spent)

| Feature | Description |
|--------|-------------|
| MntWines | Amount spent on wines |
| MntFruits | Amount spent on fruits |
| MntMeatProducts | Amount spent on meat |
| MntFishProducts | Amount spent on fish |
| MntSweetProducts | Amount spent on sweets |
| MntGoldProds | Amount spent on gold |

---

### 3️⃣ Purchase Behaviour (Frequency)

| Feature | Description |
|--------|-------------|
| NumDealsPurchases | Purchases using discounts |
| NumWebPurchases | Website purchases |
| NumCatalogPurchases | Catalog purchases |
| NumStorePurchases | Store purchases |
| NumWebVisitsMonth | Monthly website visits |

---

### 4️⃣ Customer Feedback

| Feature | Description |
|--------|-------------|
| Recency | Days since last purchase |
| Complain | Customer complaint (1 = Yes, 0 = No) |

---

## 🧠 Machine Learning Approach

This project uses **Unsupervised Learning** techniques to cluster customers.

### Algorithms Used:

- K-Means Clustering
- Hierarchical Clustering
- DBSCAN (Optional)

---

## 🔍 Project Workflow

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Feature Scaling  
5. Dimensionality Reduction (PCA)  
6. Clustering Model Training  
7. Optimal Cluster Selection  
8. Cluster Visualization  
9. Customer Segment Analysis  
10. Business Insights Generation  

---

## 📈 Evaluation Techniques

- Elbow Method
- Silhouette Score
- Davies-Bouldin Index
- Cluster Visualization (PCA / t-SNE)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---
---

## 📊 Expected Output

The system will generate:

- Customer clusters
- Cluster visualizations
- Customer segment insights
- Marketing recommendations

Example clusters:

- High-Value Customers
- Discount Seekers
- Frequent Buyers
- Low Engagement Customers
- Churn-Risk Customers

---

## 🚀 Business Impact

This system helps SmartCart:

- Improve marketing ROI
- Increase customer retention
- Identify valuable customer groups
- Personalize marketing campaigns
- Make data-driven decisions

---

## 🔮 Future Improvements

- Deploy clustering model as API
- Build customer dashboard
- Integrate real-time clustering
- Add recommendation system

---

## 👨‍💻 Author

**Aakash Thakare**

AI / Machine Learning Enthusiast  
Focused on building real-world ML systems and data-driven solutions.

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
