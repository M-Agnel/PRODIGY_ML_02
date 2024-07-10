# PRODIGY MACHINE LEARNING TASK : 02

## PROBLEM STATEMENT:
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

## INTRODUCTION:
This repository contains a project that implements a K-means clustering algorithm to group customers of a retail store based on their purchase history. 
The aim is to identify distinct customer segments to help in targeted marketing and improving customer satisfaction.Customer segmentation helps businesses understand 
the needs and preferences of different groups, enabling them to tailor their marketing strategies accordingly.

## DATASET
The dataset contains information about customers' purchase history. It includes features such as:
- Customer ID
- Age
- Gender
- Annual Income
- Spending Score

## DATA PREPROCESSING:
The first step involves preprocessing the data to ensure it is suitable for clustering:
1. **Loading the dataset**: The dataset is loaded into a Pandas DataFrame for easier manipulation.
2. **Handling missing values**: Any missing values in the dataset are handled appropriately, either by filling them with suitable values or by removing the affected rows.
3. **Normalizing or scaling features**: The features are scaled to ensure they are on a comparable scale, which is important for distance-based algorithms like K-means.
4. **Encoding categorical variables**: Categorical variables, if any, are encoded into numerical values using techniques like one-hot encoding.


## MODEL BUILDING : K-means Clustering
The K-means clustering algorithm is applied to the preprocessed data to identify customer segments:
1. **Choosing the number of clusters (K)**: The optimal number of clusters is determined using methods like the Elbow Method.
2. **Initializing centroids**: Initial centroids are selected, either randomly or using methods like K-means++.
3. **Assigning customers to clusters**: Each customer is assigned to the nearest centroid based on the distance metric (e.g., Euclidean distance).
4. **Updating centroids**: The centroids are recalculated as the mean of all customers assigned to each cluster.
5. **Repeating until convergence**: Steps 3 and 4 are repeated until the centroids no longer change significantly or a maximum number of iterations is reached.


## EVALUATION:
The clustering results are evaluated to ensure they are meaningful and effective:
1. **Elbow Method**: This method is used to determine the optimal number of clusters by plotting the sum of squared distances from each point to its assigned centroid and looking for an "elbow" in the plot.
2. **Silhouette Score**: This score measures how similar an object is to its own cluster compared to other clusters. A higher silhouette score indicates better-defined clusters.
3. **Cluster Visualization**: The clusters are visualized using scatter plots to visually inspect the separation between clusters and their compactness.

## CONCLUSION:
This project demonstrates how K-means clustering can be used to segment customers based on their purchase history. The identified segments can help in understanding customer behavior and developing targeted marketing strategies.

Feel free to clarify your doubts.
Email : magnel2001@gmail.com
