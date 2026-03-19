Machine Learning: Unsupervised Learning (Part 2)
This repository focuses on Unsupervised Learning techniques used to discover hidden patterns and structures in unlabeled data. It specifically covers clustering algorithms and dimensionality reduction methods.

🚀 Projects Included
1. K-Means Clustering
Clustering was performed across two distinct scenarios to identify group patterns:

Customer Segmentation: Grouping customers based on Age and Spending Score to identify behavioral segments.

Fruit Classification: Creating clusters based on Fruit Size (cm) and Quantity to observe pattern-based groupings.

2. Principal Component Analysis (PCA)
PCA was implemented to handle high-dimensional data (including features like Age, Income, Spending, and Savings):

Data Normalization: Utilized StandardScaler to ensure all features were on a comparable scale.

Dimensionality Reduction: Reduced 4 original features into 2 Principal Components (PCA1 and PCA2).

Result: The first two components successfully captured 99.65% of the total variance, indicating highly effective dimensionality reduction with minimal information loss.

🛠️ Tech Stack
Python: Core programming logic.

Pandas: Data manipulation and frame handling.

Scikit-Learn: Implementation of KMeans, PCA, and StandardScaler.

Matplotlib: Data visualization and plotting.

📊 Visualizations
The project utilizes Scatter Plots to effectively communicate results:

Cluster Separation: Visualizing the boundaries and differences between various data groups.

PCA Projection: Providing a clear 2D view of complex, high-dimensional data patterns to identify the underlying variance.
