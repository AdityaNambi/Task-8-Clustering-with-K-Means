# Task-8-Clustering-with-K-Means
Performing unsupervised learning with K-Means clustering.

1. Load and Prepare Data
We load the dataset and select the numerical features: Annual Income and Spending Score. These are scaled using StandardScaler to ensure fair contribution to clustering.

2. PCA for Visualization
We apply PCA to reduce the data to 2 dimensions. This helps visualize how the data points are spread and whether natural clusters exist.

3. Elbow Method
We use the Elbow Method by plotting inertia for K values from 1 to 10. The “elbow” point in the curve suggests the optimal number of clusters.

4. Fit K-Means and Visualize
Using the chosen K (e.g., 5), we fit the K-Means model and assign each point to a cluster. The clusters are visualized in 2D using the PCA output.

5. Evaluate with Silhouette Score
The Silhouette Score is computed to evaluate cluster quality. A higher score means the clusters are well-separated and consistent.
