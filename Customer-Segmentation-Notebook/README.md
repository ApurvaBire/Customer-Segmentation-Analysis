# 📊 Customer Segmentation — Clustering Analysis (Notebook)

## 📌 Overview

This folder contains the Jupyter Notebook used to perform customer segmentation using unsupervised machine learning techniques.

Customers are grouped based on their **Annual Income** and **Spending Score** to identify different purchasing behaviors and meaningful market segments.

---

## 📂 Contents

* `customer_segmentation.ipynb` — Notebook with full analysis
* `Mall_Customers.csv` — Dataset used for clustering

---

## 🗂️ Dataset Features

* CustomerID — Unique customer identifier
* Gender — Male or Female
* Age — Age of the customer
* Annual Income (k$) — Annual income in thousands
* Spending Score (1–100) — Customer spending behavior score

---

## ⚙️ Methods Used

### 🔹 K-Means Clustering

K-Means is an unsupervised machine learning algorithm that groups customers into **K clusters based on similarity**.

* Customers in the same cluster are more similar to each other
* Similarity is measured using distance (Euclidean distance)
* Helps identify distinct customer segments

---

### 🔹 Elbow Method

The Elbow Method helps determine the optimal number of clusters (K).

* Calculates **WCSS (Within Cluster Sum of Squares)** for different K values
* WCSS measures how compact the clusters are
* Lower WCSS indicates better clustering
* The point where the decrease slows down (forming an “elbow”) is chosen as the best K

---

## 📊 Outcome

The analysis divides customers into meaningful groups such as low-spending, average, and high-value customers, helping businesses understand customer behavior and design targeted marketing strategies.

---

## ▶️ How to Run

1. Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

2. Open the notebook and run all cells to reproduce the analysis.

---

##  Note

This folder contains only the data analysis and clustering work.
The interactive business dashboard is available in the Power BI folder.

