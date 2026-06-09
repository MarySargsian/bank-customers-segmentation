# bank-customers-segmentation
# Bank Customer Segmentation using Multiple Clustering Techniques

## Overview

This project explores customer segmentation in the banking sector using several unsupervised machine learning techniques. The goal is to identify distinct groups of credit card customers based on their spending behavior, payment habits, credit utilization, and account activity.

The analysis covers the complete data science workflow, including data preprocessing, feature transformation, dimensionality reduction, clustering, model evaluation, and business interpretation of the resulting customer segments.

---

## Dataset

The dataset contains approximately **8,950 customers** and **18 behavioral variables** describing credit card usage over a six-month period.

### Examples of available features:

* Account balance
* Purchase amounts
* Cash advances
* Credit limit
* Payment behavior
* Frequency-based usage metrics

**Source:** Kaggle Credit Card Customer Dataset

---

## Project Workflow

### 1. Data Preprocessing

* Missing value treatment
* Duplicate detection
* Outlier analysis
* Feature scaling and normalization
* Yeo-Johnson transformation for skewed variables

### 2. Dimensionality Reduction

Principal Component Analysis (**PCA**) was used to:

* Reduce dimensionality
* Improve clustering performance
* Visualize customer groups
* Interpret underlying behavioral patterns

### 3. Clustering Methods

Several clustering approaches were implemented and compared.

#### K-Means Clustering

* Elbow Method
* Silhouette Analysis
* Cluster interpretation

#### DBSCAN

* Density-based clustering
* Automatic outlier detection
* k-NN distance analysis for epsilon selection

#### Agglomerative Clustering

* Hierarchical clustering
* Dendrogram analysis
* Segment interpretation

#### Spectral Clustering

* Graph-based clustering
* Similarity matrix construction
* Non-linear cluster detection

#### Gaussian Mixture Models (GMM)

* Probabilistic clustering
* BIC and AIC model selection
* Soft cluster assignment

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Plotly
* Yellowbrick
* Kneed

---

## Key Results

The analysis identified multiple customer segments with distinct financial behaviors, including:

* High-value customers with large balances and high spending activity
* Customers relying heavily on cash advances
* Low-activity customers with limited card usage
* Frequent transactors who regularly repay balances
* Distinct behavioral groups with different credit utilization patterns

### Business Applications

These segments can support:

* Personalized marketing campaigns
* Credit risk assessment
* Customer retention strategies
* Product recommendation systems
* Portfolio management decisions

---



