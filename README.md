# task-8-k-mean-clustering
# Summary: K-Means Clustering on Mall Customers Dataset
Objective: Perform customer segmentation using K-Means clustering and evaluate cluster quality.

# Steps Performed:
Data Loading and Preprocessing:

Loaded the Mall_Customers.csv dataset.

Selected and standardized numerical features using StandardScaler.

Dimensionality Reduction (Optional):

Applied PCA to reduce features to 2D for easier visualization.

K-Means Clustering:

Fitted K-Means with an initial number of clusters (K=3).

Assigned cluster labels to customers.

Elbow Method:

Plotted Within-Cluster Sum of Squares (Inertia) for K = 1 to 10 to identify the optimal number of clusters.

Cluster Visualization:

Visualized the clusters in 2D using PCA-reduced components.

Color-coded points by their cluster labels.

Clustering Evaluation:

Calculated the Silhouette Score to assess cluster quality.

Current score: 0.33, suggesting moderate clustering.

Suggestions for improvement: experiment with different K, feature selection, or alternate algorithms.
