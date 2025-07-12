# 🧠 Customer Segmentation using K-Means Clustering

This project performs **Customer Segmentation** on mall customer data using the **K-Means Clustering** algorithm. The goal is to group customers into clusters based on their **Annual Income** and **Spending Score**, which can help businesses improve marketing strategies by targeting specific customer groups.

---

## 📌 Problem Statement

Businesses often struggle to understand the types of customers they serve. Using Machine Learning, we can group customers into distinct segments to identify high spenders, budget-conscious shoppers, and more — helping in focused marketing campaigns.

---

## 🚀 Technologies & Libraries Used

- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn (KMeans, PCA, StandardScaler)**

---

## 📂 Dataset Used

- **Mall_Customers.csv**
- Contains the following columns:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## 🧪 ML Pipeline Steps

1. **Data Loading** – Using Pandas to load `.csv` data  
2. **Exploratory Data Analysis (EDA)** – Visualizing distributions, correlation, and pair plots  
3. **Preprocessing** – Scaling features using `StandardScaler`  
4. **Optimal Clusters** – Using the **Elbow Method** to choose the best value of `k`  
5. **Clustering** – Applying `KMeans` algorithm  
6. **Dimensionality Reduction** – Optional: Used **PCA** for better visualization  
7. **Result Visualization** – Plotting clusters in 2D space

---

## 📈 Visual Output

- Elbow curve showing optimal `k`
- 2D cluster plots using PCA
- Color-coded segmentation of customer types

---

## 🔍 Sample Output

| Cluster | Description               |
|---------|---------------------------|
| 0       | High Income, High Spend   |
| 1       | Low Income, Low Spend     |
| 2       | Average Income, High Spend|
| ...     | ...                       |

---

## 💡 Key Learnings

- Understanding of **Unsupervised Learning**
- Practical use of **KMeans** for business use cases
- Applying **StandardScaler** and **PCA**
- Real-world application of **Customer Segmentation**

---

## 📁 Project Structure

---

## 🔗 Links

- 📂 **Dataset**: Dataset used for this project was taken from Kaggle and contains mall customer profiles with annual income and spending score.
- 💻 **GitHub Repo**:  https://github.com/pallavinegi/Customer-segmentation-ML
  

---

## 👩‍💻 Author

**Pallavi Negi**  
B.Tech CSE | Aspiring ML Engineer  
📧 Email: pallavin167@gmail.com  
🌐 GitHub: [https://github.com/pallavinegi](https://github.com/pallavinegi)

---



