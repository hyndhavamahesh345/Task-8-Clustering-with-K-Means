## 📌 Task 8: AI & ML Internship Assignment  
# 💫 Mall Customer Segmentation - K-Means Clustering

This repository contains a clustering project using the **K-Means** algorithm on the Mall Customers dataset. This task is part of the **AI & ML Internship** program and focuses on performing **unsupervised learning** to group customers based on behavior and spending patterns.

---

## 🎯 Objective  

To implement and visualize **K-Means Clustering** for customer segmentation by:  
- Identifying optimal clusters using the **Elbow Method**  
- Evaluating cluster performance with the **Silhouette Score**  
- Understanding customer groupings  
- Applying PCA for better 2D visualization of clusters  

---

## 🧰 Tools and Libraries Used  

- Python  
- Google Colab  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## 📂 Dataset  

The dataset used is the **Mall Customers Dataset**, provided as `Mall_Customers.csv`.  
It contains customer demographic and behavioral data such as:  
- `Age`  
- `Annual Income (k$)`  
- `Spending Score (1-100)`  

These features are used to identify customer segments.

---

## 📊 What Was Done  

1. **Loaded and explored the dataset**  
   - Checked columns, data types, and feature distributions  
   - Selected relevant features: `Annual Income` and `Spending Score`  

2. **Preprocessed the data**  
   - Standardized the selected features using `StandardScaler`  
   - Prepared data for clustering  

3. **Applied the Elbow Method**  
   - Computed inertia for k = 1 to 10  
   - Determined the optimal number of clusters (k = 5)  

4. **Trained K-Means Clustering Model**  
   - Used `k=5` to segment customers  
   - Assigned cluster labels to the dataset  

5. **Visualized Clusters**  
   - Used scatter plots to visualize customer groups  
   - Each cluster represented with a unique color  

6. **Evaluated Clustering Performance**  
   - Computed **Silhouette Score** to evaluate the compactness and separation of clusters  

7. **(Optional) Applied PCA for 2D Cluster Visualization**  
   - Reduced dimensions for visualization  
   - Plotted PCA-based cluster separation  

---

## 🔍 Key Insights  

- 🧍‍♂️ Customers were grouped into 5 distinct segments based on income and spending behavior  
- 💰 High-income & high-spending customers formed a clear cluster  
- 🎯 The Elbow method helped objectively choose the best number of clusters  
- 🧪 A **Silhouette Score of ~0.55** indicates reasonably good clustering  

---

## 🧪 Results Summary  

| Evaluation Method   | Result |
|---------------------|--------|
| Optimal Clusters (k) | 5      |
| Silhouette Score     | 0.5536 |

---

## 📌 Concepts You’ll Learn  

- Unsupervised Learning  
- K-Means Clustering  
- Elbow Method  
- Silhouette Score  
- PCA for Visualization  

---

