# Unsupervised Machine Learning: Clustering Analysis

## Project Overview
This project explores the application of unsupervised machine learning algorithms to segment and analyze a trade-related dataset. The main objective is to identify meaningful clusters within the data using various clustering techniques, such as K-Means, DBSCAN, and Birch. The analysis focuses on determining the optimal number of clusters, analyzing the characteristics of each cluster, and deriving actionable business insights from the findings.

## Problem Statement
The goal of this project is to segment the dataset into distinct clusters based on various trade-related features. This segmentation will help in understanding hidden patterns, relationships, and trends within the data, which can be used for strategic business decision-making. The key objectives are:

- Identify homogeneous groups (clusters) within the dataset.
- Analyze and interpret the distinguishing features of each cluster.
- Provide actionable insights and recommendations based on the clustering results.

## Key Features
- **Clustering Algorithms**: Implementation of K-Means, DBSCAN, and Birch clustering algorithms.
- **Cluster Evaluation**: Use of performance metrics like Silhouette Coefficient and Davies-Bouldin Index to assess clustering quality.
- **Optimal Cluster Selection**: Identification of the optimal number of clusters through algorithm evaluation and hyperparameter tuning.
- **Cluster Characteristics**: In-depth analysis of cluster profiles and patterns for actionable business insights.
- **Data Preprocessing**: Handling of categorical and numerical data, with feature engineering for enhanced analysis (e.g., creation of `Total_Value`).

## Dataset
The dataset used in this project contains a total of 15,000 trade transactions, with a sample size of 5,001 rows selected for analysis. Key variables include:

- **Categorical Variables**: Country, Product, Import/Export, Category, Port, Shipping Method, Supplier, Customer, Payment Terms (nominal and ordinal data).
- **Non-Categorical Variables**: Quantity, Value, Weight (numerical data).
- **Derived Variables**: `Total_Value` (calculated as the product of Value and Quantity), for deeper analysis of trade volumes.

The data is stored in CSV format and is structured to reflect international trade transactions over time.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment**: Google Colab
- **Version Control**: GitHub (for version tracking and collaboration)

## Methodology
1. **Data Preprocessing**: Data cleaning, encoding of ordinal variables, and scaling of numeric features to prepare the dataset for clustering.
2. **Clustering**: Application of K-Means, DBSCAN, and Birch algorithms to segment the data into clusters.
3. **Evaluation**: Use of the Silhouette Coefficient and Davies-Bouldin Index to assess the quality of clusters and select the optimal model.
4. **Analysis**: Detailed analysis of each cluster to understand the nature of the trade transactions and identify trends.

## Insights and Applications
- **Cluster Insights**: K-Means, DBSCAN, and Birch produce different insights, with K-Means showing the most distinct clusters based on transaction value and type (import/export).
- **Business Applications**: The findings can be used for strategic decision-making, such as targeted marketing for high-value exporters or cost-optimization strategies for smaller transactions.

## Contributors
- **Krishnendu Adhikary**
