# Cryptocurrency Market Data Analysis

This project involves the analysis of cryptocurrency market data using Python, Pandas, hvPlot, and Scikit-learn. The goal is to understand the underlying patterns in the data by applying K-Means clustering on both the original and PCA-transformed data.

## Table of Contents
1. Data
2. Dependencies
3. Analysis
4. Results

## Data
The data used in this project is stored in a CSV file named `crypto_market_data.csv`.

## Dependencies
The project uses the following Python libraries:
- Pandas
- hvPlot
- Scikit-learn (KMeans, PCA, StandardScaler)

## Analysis
The analysis involves several steps:

1. **Data Loading and Exploration:** The data is loaded into a Pandas DataFrame and explored using methods like `head()` and `describe()`. 

2. **Data Visualization:** The data is visualized using hvPlot to understand the underlying patterns.

3. **Data Preprocessing:** The data is scaled using `StandardScaler` to ensure that the features have a mean of 0 and a standard deviation of 1.

4. **Clustering with K-Means:** The K-Means algorithm is applied to the scaled data to group the cryptocurrencies into clusters. The optimal number of clusters is determined using the Elbow method.

5. **Dimensionality Reduction with PCA:** Principal Component Analysis (PCA) is used to reduce the dimensionality of the data. The K-Means algorithm is then applied to the PCA-transformed data.

6. **Cluster Visualization:** The clusters are visualized using hvPlot for both the original and PCA-transformed data.

## Results
The results of the analysis include the optimal number of clusters for K-Means, the inertia values for different numbers of clusters, and the scatter plots visualizing the clusters for the original and PCA-transformed data. The impact of using fewer features (PCA-transformed data) on the clustering is evaluated by comparing the clustering results of the original and PCA-transformed data.

Please note that the specific results depend on the data and may vary if the data changes. The code can be easily adapted to analyze different datasets or to use different machine learning algorithms.
