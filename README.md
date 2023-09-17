# Customer Segmentation for a Shopping Mall using Unsupervised Learning

## Overview

This project focuses on customer segmentation for a shopping mall using unsupervised learning techniques, specifically K-means clustering. The goal is to group mall customers based on their spending behavior and income, allowing the mall to tailor its marketing strategies and tenant selection to different customer segments.

## Key Highlights
Data Exploration:

* Conducted univariate and bivariate analysis to gain insights into customer behavior.
* Examined the distribution of individual variables such as spending behavior and income.
* Explored relationships between variables to identify potential patterns.

## K-Means Clustering:

* Implemented K-means clustering, an unsupervised learning algorithm, to segment mall customers.
* Utilized the elbow technique to determine the optimal number of clusters for customer segmentation. This involved fitting K-means models with varying numbers of clusters and plotting the within-cluster sum of squares (inertia) to identify the "elbow point" where adding more clusters does not significantly reduce inertia.
* Employed silhouette analysis to further validate the chosen number of clusters. Silhouette scores measure the quality of clustering by evaluating the distance between data points within the same cluster and between different clusters.
* These segments provide actionable insights into customer characteristics, helping the mall tailor its strategies.

## Files
* Mall_customers.csv: The dataset containing customer information, including spending behavior and income.
* customer_segmentation.ipynb: Jupyter Notebook containing the code and analysis for customer segmentation.
* segmented_data.csv: The CSV file containing the final customer segmentation results.