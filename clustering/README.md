# Clustering Analysis

This project explores the application of clustering algorithms to three distinct datasets. We utilize three popular clustering algorithms: K-means, DBSCAN, and Fuzzy C-Means (FCM) to group data points into clusters. Here's a brief overview:

1. **Data Preparation**: We start by importing necessary libraries and loading three datasets (`first_clustering_dataset.csv`, `second_clustering_dataset.csv`, and `third_clustering_dataset.csv`) into NumPy arrays after reading them with Pandas. Data scaling is performed using standardization.

2. **Visualization and Analysis**:
   - For each dataset, we visualize it in 2D plots to gain insights into its structure.
   - We analyze and make algorithm choices based on the visualizations:
     - For the **first dataset**, K-means or FCM is preferred.
     - For the **second dataset**, K-means is recommended due to its performance.
     - For the **third dataset**, K-means or FCM is a suitable choice.

3. **Algorithm Implementation**:
   - We define functions for each algorithm and additional utility functions to find optimal parameters like the number of clusters (`K-means`), `eps`, and `min_samples` (`DBSCAN`).
   - We execute these algorithms on each dataset, visualizing the results and computing relevant metrics.

4. **Model Selection**:
   - To ensure robustness, we run each algorithm 200 times for each dataset and record the best models based on error and coefficients:
     - For the **first dataset**, K-means performs best.
     - For the **second dataset**, K-means yields the lowest error.
     - For the **third dataset**, K-means delivers the lowest error.

5. **Results and Evaluation**:
   - We display the errors and coefficients for each algorithm for all three datasets in separate DataFrames.

By analyzing the results, you can choose the most suitable clustering algorithm for your specific dataset and requirements.