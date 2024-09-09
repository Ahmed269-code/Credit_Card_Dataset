# Credit_Card_Dataset
Credit_Card_Dataset with PCA and K_means

Project Workflow
1. Data Preprocessing & Exploration:
Loaded and cleaned the dataset.
Addressed missing values using business logic and statistical imputations.
Filtered extreme outliers to ensure reliable and accurate analysis.
2. Data Visualization:
Used Matplotlib and Seaborn to visualize data distributions and correlations.
Generated histograms for numerical features and heatmaps to highlight feature correlations.
3. Outlier Detection:
Identified outliers using the Interquartile Range (IQR) method.
Counted outliers in each feature to assess the overall distribution.
4. Dimensionality Reduction with PCA:
Applied Principal Component Analysis (PCA) to reduce the data's dimensionality, retaining most of the variance.
Visualized the data in 2D, allowing for better interpretation of natural customer clusters.
5. Clustering Techniques:
Implemented K-Means Clustering for customer segmentation.
Determined the optimal number of clusters using the Elbow Method and Silhouette Score.
Experimented with DBSCAN to detect non-linear clusters and noise.
6. Insights & Visualizations:
Visualized customer segments by plotting clusters on PCA-transformed data.
Compared K-Means and DBSCAN to evaluate their performance in detecting meaningful customer segments.
Key Learnings
This project provided valuable insights into how clustering techniques can segment customers effectively in real-world datasets. The visualizations from PCA helped enhance the interpretability of the clusters.

Conclusion
Through this analysis, I deepened my understanding of clustering methods and dimensionality reduction, and I’m excited to apply these techniques to future projects.

