# Customer Segmentation Project

## Overview

This project aims to segment customers based on various features like Age, Annual Income, and Spending Score to help businesses understand different customer groups. Using the **Mall Customers** dataset, we perform data analysis and customer segmentation using unsupervised machine learning techniques like **K-Means Clustering**.

## Dataset

The dataset used in this project is the [Mall Customers Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python) from Kaggle. It contains information about 200 customers with the following columns:

- **CustomerID**: Unique ID for each customer
- **Gender**: Gender of the customer (Male/Female)
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars
- **Spending Score (1-100)**: A score assigned to each customer based on their spending behavior

## Project Structure

- **Data Preprocessing**: We clean and preprocess the data, handle missing values, and convert categorical variables (like Gender) into numeric values.
- **Exploratory Data Analysis (EDA)**: We explore the dataset through visualizations to understand the distribution of key variables like Age, Income, and Spending Score.
- **Clustering**: We apply unsupervised learning techniques like **K-Means Clustering**, **Hierarchical Clustering**, and **DBSCAN** to group customers into segments.
- **Visualization**: We visualize the clusters and the relationship between different features (e.g., Age vs Income) using 2D and 3D plots.

## Techniques Used

- **K-Means Clustering**: A clustering algorithm to partition customers into K distinct groups.
- **Elbow Method**: Used to determine the optimal number of clusters for K-Means.
- **PCA**: Principal Component Analysis used for dimensionality reduction to visualize the clustering results.
- **Seaborn/Matplotlib**: Data visualization libraries to create various plots and graphs.

## Steps to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
