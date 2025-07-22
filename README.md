# 🛍️ Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment customers of a retail store based on their **Annual Income** and **Spending Score**. It helps in understanding different customer groups for targeted marketing and better customer relationship management.

---

## 📂 Dataset

**Filename**: `Mall_Customers.csv`

**Features:**
- `CustomerID` – Unique customer identifier  
- `Genre` – Gender of the customer  
- `Age` – Age of the customer  
- `Annual Income (k$)` – Annual income in thousands  
- `Spending Score (1-100)` – A score assigned by the mall based on customer behavior and spending patterns  

---

## 🧠 Objective

To segment customers into distinct groups using **K-Means Clustering** based on their purchase behavior. This can help in:
- Personalized marketing
- Loyalty program planning
- Product recommendation systems

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- StandardScaler (for data normalization)

---

## 📊 Methodology

1. **Data Preprocessing**
   - Selected key features: `Annual Income (k$)` and `Spending Score (1-100)`
   - Scaled the data using StandardScaler

2. **Elbow Method**
   - Used to determine the optimal number of clusters (k)
   - Optimal k ≈ 5

3. **Model Training**
   - Applied K-Means with `k=5`
   - Assigned cluster labels to each customer

4. **Visualization**
   - Plotted customer clusters using scatter plots
   - Centroids are marked to represent cluster centers

---

## 📌 Results

- The customers were grouped into 5 distinct clusters.
- Clusters show different spending habits and income levels, useful for strategy development.

---
