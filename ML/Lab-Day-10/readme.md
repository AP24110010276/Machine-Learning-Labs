
# K-Means Clustering Algorithm in Machine Learning

## Project Overview

This project demonstrates K-Means Clustering, an unsupervised machine learning algorithm used to group similar data points into clusters.

The project uses the Wholesale Customers dataset to perform customer segmentation based on their spending habits across different product categories.

K-Means++ initialization and the Elbow Method are used to improve clustering and identify a suitable number of clusters.

## Objectives

- Understand the K-Means Clustering algorithm.
- Perform customer segmentation.
- Apply K-Means++ initialization.
- Standardize the dataset.
- Find the optimal number of clusters using the Elbow Method.
- Visualize the generated clusters.
- Evaluate clustering using Inertia and Silhouette Score.

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

Wholesale Customers Dataset from the UCI Machine Learning Repository.

Dataset contains customer spending information on:
- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen

It also includes Channel and Region information.

## Algorithm

K-Means is an unsupervised learning algorithm that divides data into K clusters based on similarity.

### Working Steps

1. Select the number of clusters (K).
2. Initialize centroids using K-Means++.
3. Assign data points to their nearest centroid.
4. Recalculate the centroids.
5. Repeat until convergence.
6. Obtain the final clusters.

## Project Workflow

1. Import required libraries.
2. Load the Wholesale Customers dataset.
3. Explore and understand the dataset.
4. Select relevant features.
5. Visualize the original dataset.
6. Standardize the data.
7. Apply K-Means++ clustering.
8. Determine the optimal K using the Elbow Method.
9. Perform final clustering.
10. Visualize clusters using PCA.
11. Evaluate using Silhouette Score.
12. Save the final clustering results.

## Evaluation Metrics

- **Inertia:** Measures the sum of squared distances between data points and their assigned cluster centroids. Lower values indicate more compact clusters.
- **Silhouette Score:** Measures how similar a data point is to its own cluster compared to other clusters. Higher values generally indicate better-separated clusters.

## Results

The project performs customer segmentation using five clusters.

The results include:
- Elbow Curve visualization.
- Customer cluster visualization using PCA.
- Inertia value.
- Silhouette Score.
- Cluster distribution.
- Cluster-wise average spending.

## Applications

- Customer Segmentation
- Document Clustering
- Image Segmentation
- Recommendation Systems
- Market Analysis

## Advantages

- Easy to understand and implement.
- Efficient for large datasets.
- Works well with clearly separated clusters.
- K-Means++ improves centroid initialization.

## Disadvantages

- Requires selecting the number of clusters.
- Sensitive to outliers.
- Results can depend on centroid initialization.
- May not perform well with clusters of different sizes and densities.

## Conclusion

This project demonstrates the implementation of K-Means Clustering for customer segmentation using Python. The Elbow Method helps identify a suitable number of clusters, while K-Means++ provides improved centroid initialization.

The project helps understand how unsupervised machine learning can identify patterns and group customers based on their spending behavior.

## Reference

Analytics Vidhya - Comprehensive Guide to K-Means Clustering

https://www.analyticsvidhya.com/blog/2019/08/comprehensive-guide-k-means-clustering/

