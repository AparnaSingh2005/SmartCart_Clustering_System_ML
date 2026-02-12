#  SmartCart Customer Clustering System

##  Overview

SmartCart is a multi-country e-commerce platform that collected **2,240 customer records with 22 features** covering demographics, purchasing behavior, website activity, and engagement. The platform currently applies **generic marketing strategies**, leading to poor personalization, missed retention opportunities, and inefficient campaigns.
This project builds an **intelligent customer segmentation system** using **unsupervised machine learning** to identify meaningful customer clusters and enable **data-driven marketing and retention strategies**.

##  Objectives

* Discover hidden patterns in customer behavior
* Segment customers based on purchase, engagement, and loyalty metrics
* Identify high-value and churn-prone customers
* Support personalized marketing and business decisions

## Solution Approach

* Applied **unsupervised clustering algorithms** to group similar customers
* Used **feature scaling and PCA** for better clustering performance
* Evaluated clusters using **Elbow Method and Silhouette Score**
* Interpreted clusters for actionable business insights

## Tech Stack

* **Language:** Python
* **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
* **ML Techniques:** K-Means Clustering, PCA, Agglomerative Clustering
* **Environment:** Jupyter Notebook

## Dataset

* **Records:** 2,240 customers
* **Features:** 22
* **Includes:** Demographics, purchase history, website activity, response metrics
Dataset not included due to privacy constraints.

## Methodology

1. Data cleaning & preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature scaling & dimensionality reduction (PCA)
4. Optimal cluster selection (Elbow & Silhouette)
5. Customer segmentation using K-Means , Agglomerative clustering
6. Cluster interpretation & visualization

## Key Results

* Identified distinct customer segments:
  * High-value loyal customers
  * Moderate-value frequent buyers
  * Low-engagement / churn-risk customers
* Improved understanding of customer behavior
* Enabled targeted marketing & retention strategies

##  Future Work

* Deploy model using **Streamlit** or **Flask**
* Automate re-clustering with new customer data
* Integrate with recommendation systems


 ** If you find this project useful, consider starring the reposito
