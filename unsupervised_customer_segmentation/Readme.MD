# 🧠 Credit Card Customer Segmentation (Unsupervised Learning)

This project uses unsupervised machine learning to segment credit card customers based on their transaction behavior. The goal is to identify different customer groups to help businesses personalize offers, improve targeting, and understand usage patterns.

## 📌 What I Did
- Cleaned and preprocessed the dataset (handled missing values, skewness, and outliers)
- Scaled the features using `StandardScaler`
- Used the Elbow Method to find the optimal number of clusters
- Applied K-Means Clustering (`k=4`)
- Visualized clusters with PCA
- Analyzed cluster profiles to interpret customer behavior

## 📊 Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

## 📁 Dataset
Kaggle: [Credit Card Dataset for Clustering](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)

## 📈 Output
- `credit_card_clustered_customers.csv` → Cleaned data with cluster labels
- PCA scatter plot of clustered customers
- Bar charts for cluster-wise feature comparison

---

🚀 Feel free to fork this repo or build on top of it!
