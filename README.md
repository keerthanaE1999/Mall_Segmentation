# 🧠 Customer Segmentation using K-Means Clustering

This project demonstrates how to apply *K-Means Clustering*, a popular unsupervised machine learning algorithm, to segment customers based on their behavior and demographic attributes. The goal is to identify distinct customer groups to support targeted marketing strategies and improve business decision-making.

---

## 📁 Project Structure

- customer_segmentation.ipynb – Jupyter Notebook containing the full analysis, modeling, and visualizations.  
- data.csv – Dataset used for clustering (Mall Customer Segmentation Data).  
- requirements.txt – List of Python libraries required to run the project.

---

## 🎯 Project Objective

To group customers into meaningful segments based on features such as:

- Age  
- Annual Income (in $1000s)  
- Spending Score (1–100)  

These clusters can be used to tailor marketing campaigns and enhance customer engagement.

---

## 📊 Dataset Information

*Source*: Mall Customer Segmentation Dataset (public domain)

*Columns:*
- CustomerID: Unique identifier for each customer  
- Gender: Male or Female  
- Age: Customer’s age  
- Annual Income (k$): Income in thousands  
- Spending Score (1–100): Score assigned by the mall based on spending patterns

---

## 🔧 Methodology

1. *Data Loading & Preliminary Analysis*  
2. *Preprocessing & Feature Selection*  
3. *Finding the Optimal Number of Clusters* (Elbow Method)  
4. *Model Training with K-Means*  
5. *Cluster Analysis & Visualization*

---

## 📈 Key Visualizations

- *Elbow Method Plot* – Helps determine the optimal number of clusters  
- *2D Scatter Plots* – Visualize customer segments  
- *Colored Cluster Mapping* – Clear interpretation of grouped behavior based on features like income and spending

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation
