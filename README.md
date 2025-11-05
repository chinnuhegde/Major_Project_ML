# Customer Segmentation Using Unsupervised Learning

## 📌 Project Overview
This project applies **K-Means Clustering** to segment mall customers based on their purchasing behavior. The goal is to identify different customer groups so businesses can target them more effectively and improve marketing strategies.

## 🧠 Methodology
1. **Dataset Used:** Mall Customers Dataset  
2. **Preprocessing Steps:**
   - Removed non-predictive *CustomerID*
   - Encoded *Gender*
   - Standardized numeric features
3. **Clustering Technique:** K-Means Algorithm
4. **Cluster Validation:** Elbow Method & Silhouette Score
5. **Number of Clusters Selected:** **k = 5**

## 📊 Results
- The **Silhouette Score** obtained was **~0.27**, indicating moderate clustering quality.
- Five customer segments were formed based on **Annual Income** and **Spending Score**.
- Visualizations showed distinct but partially overlapping groups, which is common in real-world data.

## 🧩 Customer Segment Insights
| Cluster | Characteristics | Interpretation |
|--------|----------------|----------------|
| Cluster 0 | High income, low spending | Conservative / Selective Buyers |
| Cluster 1 | Low income, low spending | Less Active / Budget Conscious |
| Cluster 2 | Moderate income, high spending | Engaged / Loyal Customers |
| Cluster 3 | High income, high spending | Premium / Ideal Target Group |
| Cluster 4 | Low income, high spending | Impulsive / Offer-Oriented Customers |

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## 🚀 How to Run
1. Upload the dataset (`Mall_Customers.csv`) to your environment.
2. Run the notebook or script step-by-step.
3. The output CSV and cluster plots will be generated automatically.

## ✅ Conclusion
K-Means clustering helps reveal meaningful customer segments based on purchasing behavior. These insights can support **targeted marketing, personalized offers, and data-driven business decisions**.

---

