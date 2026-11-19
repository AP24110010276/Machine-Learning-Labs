
# Hierarchical Clustering in Machine Learning

## Project Overview
This project demonstrates Hierarchical Clustering, an unsupervised machine learning algorithm used to group similar data points into clusters.

The project implements Agglomerative Hierarchical Clustering using Python and visualizes the results using a dendrogram and scatter plots.

## Objectives
- Understand Hierarchical Clustering.
- Implement Agglomerative Clustering.
- Generate and visualize a dendrogram.
- Identify groups in the dataset.
- Evaluate clustering performance using the Silhouette Score.

## Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Algorithm
Agglomerative Hierarchical Clustering is a bottom-up approach.

It starts by treating each data point as an individual cluster and repeatedly merges the closest clusters until the required number of clusters is obtained.

## Project Workflow
1. Import required libraries.
2. Generate the sample dataset.
3. Explore and visualize the dataset.
4. Standardize the features.
5. Generate the dendrogram.
6. Apply Agglomerative Clustering.
7. Visualize the generated clusters.
8. Evaluate using the Silhouette Score.
9. Save the clustered dataset.

## Results
The algorithm groups the generated dataset into three clusters.

The results are visualized using:
- Original dataset scatter plot.
- Hierarchical clustering dendrogram.
- Final cluster visualization.
- Silhouette Score.

## How to Run
1. Open the Google Colab notebook.
2. Run all cells sequentially.
3. Observe the dendrogram and clustering results.
4. Download the final CSV dataset.

## Advantages
- Does not require predefined cluster centers.
- Dendrogram provides a visual representation of clusters.
- Suitable for small datasets.
- Supports different linkage methods.

## Disadvantages
- Computationally expensive for large datasets.
- Requires memory for distance calculations.
- Once clusters are merged, they cannot be separated in the agglomerative process.

## Conclusion
This project demonstrates how Hierarchical Clustering can group similar data points using an agglomerative approach. Dendrogram visualization helps understand cluster formation, while the Silhouette Score evaluates clustering quality.

## Reference
Analytics Vidhya - Hierarchical Clustering in Machine Learning

https://www.analyticsvidhya.com/blog/2022/11/hierarchical-clustering-in-machine-learning/

