# Customer_segmentation
Project Description
This project aims to perform customer segmentation using the K-Means clustering algorithm on a dataset of mall customers. Customer segmentation is a crucial practice for businesses as it allows them to understand different customer groups, tailor marketing strategies, and enhance customer satisfaction.

Objective
The primary objective of this project is to segment customers into distinct groups based on their spending behavior and annual income. By identifying these segments, we can help the mall management understand customer preferences and behavior better, leading to improved customer targeting and personalized marketing efforts.

Dataset
The dataset used for this project is of the "Mall Customer Segmentation Data". It contains information about customers of a mall, including the following features:

CustomerID: Unique identifier for each customer.
Gender: Gender of the customer.
Age: Age of the customer.
Annual Income (k$): Annual income of the customer in thousands of dollars.
Spending Score (1-100): A score assigned by the mall based on customer spending behavior.
The dataset can be found here.

Project Steps
1. Data Loading and Preprocessing
Load the Data: Load the dataset using Pandas.
Data Cleaning: Check for missing values and handle them appropriately.
Feature Selection: Select relevant features for clustering. We will use 'Age', 'Annual Income (k$)', and 'Spending Score (1-100)'.
2. Data Exploration and Visualization
Descriptive Statistics: Generate summary statistics for the numerical features.
Visualize Data: Use histograms, scatter plots, and pair plots to visualize the distribution and relationships between features.
3. Data Normalization
Normalize the features using StandardScaler to ensure that they have a mean of 0 and a standard deviation of 1. This step is crucial for the K-Means algorithm to perform effectively.
4. K-Means Clustering
Determine Optimal Number of Clusters: Use the elbow method to determine the optimal number of clusters. This involves plotting the within-cluster sum of squares (WCSS) against the number of clusters and looking for the "elbow point."
Fit K-Means Model: Apply the K-Means algorithm with the optimal number of clusters.
Assign Cluster Labels: Assign cluster labels to each customer.
5. Visualization of Clusters
2D Scatter Plot: Visualize the clusters using 2D scatter plots.
6. Analysis of Clusters
Analyze the characteristics of each cluster by computing the mean values of 'Age', 'Annual Income (k$)', and 'Spending Score (1-100)' for each cluster.
Provide insights on the identified customer segments and suggest potential marketing strategies for each segment.
