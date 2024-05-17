# PRODIGY_ML_02
## Customer Segmentation
### Description of Each Set of Code
<br>
1. Imports and Data Loading:
<br>
    * Import necessary libraries and load the dataset from a CSV file.
    <br>
2. Data Exploration:
<br>
    * Display the first few rows of the dataset.
    <br>
    * Print the shape of the dataset.
    <br>
    * Show info about the dataset including column types and non-null counts.
    <br>
    * Count and display the number of duplicated rows.
    <br>
    * Display descriptive statistics for the dataset.
    <br>
3. Data Visualization - Pairplot:
<br>
    * Create a pairplot of features colored by gender.
    <br>
4. Data Visualization - Gender Distribution:
<br>
    * Create a countplot showing the distribution of gender.
    <br>
5. Data Visualization - Histograms:
<br>
    * Create histograms with KDE plots for 'Age', 'Annual Income (k$)', and 'Spending Score (1-100)'.
    <br>
6. Elbow Method and Silhouette Score Calculation:
<br>
    * Use the Elbow Method to determine the optimal number of clusters by plotting inertia.
    <br>
    * Calculate and plot silhouette scores for different numbers of clusters.
    <br>
7. K-Means Clustering:
<br>
    * Perform K-Means clustering with the optimal number of clusters.
    <br>
    * Assign cluster labels to the dataset.
    <br>
8. Cluster Visualization:
<br>
    * Create a scatter plot of customers colored by their cluster assignments based on 'Annual Income (k$)' and 'Spending Score (1-100)'.
    <br>
9. Cluster Analysis:
<br>
    * Create a DataFrame of cluster centers and display it.
    <br>
    * Count and display the number of customers in each cluster.
    <br>
10. Cluster Centers Heatmap:
<br>
    * Visualize cluster centers using a heatmap.
    <br>
11. Number of Customers in Each Cluster Bar Plot:
<br>
    * Create a bar plot showing the number of customers in each cluster.
