# 🛍️ E-Commerce Customer Segmentation Capstone

## 📌 Problem Statement

E-commerce platforms often struggle with broad, ineffective marketing campaigns that waste resources and fail to engage customers personally. This project addresses that challenge by identifying meaningful customer segments to **enable personalized marketing strategies** that increase retention, satisfaction, and sales.

---

## 🎯 Goal

Develop a **data-driven customer segmentation model** using behavioral and demographic data to:

- Improve marketing ROI
- Personalize campaigns
- Retain high-value customers
- Understand purchasing patterns

---

## 📂 Data Sources

- `E-commerce Customer Behavior.csv`  
  Includes:
  - **Demographics**: Age, Gender, City, Membership Type
  - **Purchases**: Total Spend, Items Purchased, Discounts Used
  - **Engagement**: Days Since Last Purchase, Satisfaction Level
  - **Ratings**: Average Product Ratings

---

## 🧹 Data Preparation

- Dropped 2 rows with missing `Satisfaction Level`
- Verified no duplicate rows
- Detected and analyzed outliers (e.g., in spend and item counts)
- Encoded categorical variables (e.g., Gender, Membership Type)
- Standardized numerical features before clustering

---

## 🔍 Exploratory Data Analysis (EDA)

Key Findings:
- Higher `Total Spend` and `Items Purchased` are strongly correlated
- Customers with higher `Average Ratings` and satisfaction tend to spend more
- Discount usage patterns vary by age and membership type

Visuals:
- Histograms, boxplots, and heatmaps revealed variable distributions and correlations

---

## ⚙️ Feature Engineering

Created additional insights:
- Encoded categorical variables
- Scaled features for clustering
- Prepared a cluster-friendly dataset with key variables:
  - Total Spend, Items Purchased, Satisfaction Level, etc.

---

## 🔢 Clustering & Segmentation

Used **K-Means** clustering to identify customer groups.

### 📊 Optimal Clusters: 4  
Validated using:
- **Elbow Method**
- **Silhouette Score** (~0.62)

### 📦 Customer Segments

| Cluster | Label                        | Key Traits |
|--------:|------------------------------|------------|
| 0       | Discount-Driven Occasional Shoppers | Older, mid-spenders, use discounts often |
| 1       | Young Bargain Hunters        | Very active, high spend, rely on discounts |
| 2       | Moderate Loyal Customers     | High satisfaction, steady spend, low discounts |
| 3       | High-Value Frequent Buyers   | Big spenders, very loyal, no discounts |

---

## 🤖 Baseline Model

Used **Logistic Regression** to predict cluster membership.

| Metric        | Value |
|---------------|--------|
| Accuracy      | 100%   |
| Precision     | 100%   |
| Recall        | 100%   |
| F1-Score      | 100%   |
| ROC-AUC Score | 1.00   |

✅ Model confirms clusters are **distinct and well-separated**.

---

## 📊 Visualizations Included

- Cluster Distribution Pie Chart
- Silhouette Score vs Cluster Count
- Heatmap of Cluster Centers

---

## 💡 Marketing Recommendations

| Segment | Action |
|---------|--------|
| **Occasional Shoppers** | Loyalty programs, win-back campaigns |
| **Bargain Hunters** | Flash deals, student discounts, gamified offers |
| **Loyal Moderates** | Personalized emails, early access |
| **VIPs** | Concierge service, exclusive invites, VIP clubs |

---

## ✅ Conclusion

- **Segmentation enables precision marketing**
- High ROI potential via personalized strategies
- Future steps: predict churn, forecast CLTV, integrate real-time behavior

---

## 📎 Files

- `customer_segmentation.ipynb`: Full analysis notebook
- `README.md`: This summary
- `E-commerce Customer Behavior.csv`: Raw dataset

---

## 🛠 Tools Used

- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- K-Means Clustering
- Logistic Regression
