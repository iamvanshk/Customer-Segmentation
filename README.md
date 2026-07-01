# Customer Segmentation using K-Means Clustering

## Overview

This project implements **Customer Segmentation** using the **K-Means Clustering** algorithm, an unsupervised machine learning technique. The model groups customers into different clusters based on their **Annual Income** and **Spending Score**, helping businesses understand customer behavior and create targeted marketing strategies.

---

## Dataset

- **Dataset:** Mall Customers Dataset
- **Source:** Kaggle
- **Number of Records:** 200

### Features

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

For clustering, the following features were used:

- Annual Income (k$)
- Spending Score (1-100)

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

---

## Machine Learning Algorithm

### K-Means Clustering

K-Means is an **unsupervised learning algorithm** that partitions data into K clusters by minimizing the distance between data points and their respective cluster centroids.

Project Configuration:

- Algorithm: K-Means Clustering
- Initialization: k-means++
- Number of Clusters: 5
- Random State: 0

---

## Project Workflow

1. Import the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Select relevant features
4. Determine the optimal number of clusters using the Elbow Method
5. Train the K-Means model
6. Predict customer clusters
7. Visualize the clusters and centroids

---

## Determining the Optimal Number of Clusters

The **Elbow Method** was used to determine the optimal number of clusters.

The Within Cluster Sum of Squares (WCSS) was calculated for cluster sizes ranging from **1 to 10**. Based on the elbow graph, **5 clusters** were selected as the optimal number.

Additionally, the model achieved a **Silhouette Score of approximately 0.554**, indicating a reasonable clustering structure for the selected features.

---

## Results

The K-Means model successfully divided customers into **five distinct clusters** based on their income and spending habits.

The final visualization displays:

- Five customer groups
- Cluster centroids
- Well-separated customer segments

These clusters can be used by businesses to design personalized marketing strategies and improve customer targeting.

---

## Project Structure

```
Customer-Segmentation/
│
├── Customer Segmentation.ipynb
├── Mall_Customers.csv
├── README.md
└── images/
    ├── elbow_method.png
    └── customer_clusters.png
```

---

## Key Learnings

Through this project, I learned:

- Unsupervised Machine Learning
- K-Means Clustering
- Elbow Method
- Silhouette Score
- Data Visualization
- Customer Segmentation
- Exploratory Data Analysis (EDA)

---

## Future Improvements

- Include additional features such as Age and Gender
- Compare K-Means with DBSCAN and Hierarchical Clustering
- Perform feature scaling before clustering
- Deploy the project using Streamlit
- Build an interactive dashboard for customer segmentation

---

## Author

**Vansh**

Integrated M.Sc. Mathematics | Machine Learning Enthusiast

---

## ⭐ If you found this project helpful, consider giving it a star!
