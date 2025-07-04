## Project Summary
### What We Did
We performed customer segmentation using unsupervised learning (K-Means Clustering) on mall customer data. The objective was to divide customers into distinct groups based on their income and spending habits to support targeted marketing strategies.

### Why We Did It
Businesses often need to understand their customer base to tailor offers, improve engagement, and increase revenue. Manual segmentation is subjective and inefficient. Using machine learning for clustering allows for data-driven, scalable, and repeatable customer segmentation.

### How We Did It
    1.Data Cleaning and Preprocessing:
    2.Encoded categorical data (Gender).
    3.Dropped irrelevant identifiers (CustomerID).
    4.Scaled features using StandardScaler for normalization.
    5.Feature Selection and Dimensionality Reduction:
    6.Selected key features: Annual Income (k$) and Spending Score (1-100).
    7.Applied PCA for visualization and dimensionality understanding.

### Clustering:

Used the Elbow Method with KneeLocator to determine the optimal number of clusters (K=5).
Trained a KMeans model and assigned each customer to a cluster.

Evaluation and Profiling:
Evaluated clustering performance using Silhouette Score (0.555).

Profiled each cluster based on average income, spending score, and age.

Assigned human-readable segment names to each cluster.


### Visualization and Interpretation:

Visualized customer segments on a scatter plot.

Created a mapping from cluster IDs to descriptive segment labels.

Enabled prediction for new customer entries based on trained clusters.

