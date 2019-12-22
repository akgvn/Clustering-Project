# Clustering Project for CENG474: Data Science

This repo contains the Hierarchical Clustering part for the project below.

## Project Explanation: Amyotrophic Lateral Sclerosis (ALS) Cluster Analysis

Use the [ALS dataset](https://umich.instructure.com/courses/38100/files/folder/Case_Studies/15_ALS_CaseStudy). This case-study examines the patterns, symmetries, associations and causality in a rare but devastating disease, amyotrophic lateral sclerosis (ALS). A major clinically relevant question in this biomedical study is: What patient phenotypes can be automatically and reliably identified and used to predict the change of the ALSFRS slope over time?. This problem aims to explore the data set by unsupervised learning.

- Load and prepare the data.
- Perform summary and preliminary visualization.
- Train a k-Means model on the data, select k as mentioned in DataScience COurse in UMICH.
- Evaluating the model performance by report the center of clusters and silhouette and explain details (since 100 dimensions, it is messy to use bar plot show the centers).
- Tune parameters and plot with k-means++.
- Return the model with optimal parameters and interpret the clustering results.
- Apply Hierarchical Clustering on three different linkages and compare the corresponding Silhouette plots.
- Apply DBSCAN on different minpoints and eps
- Compare the result of the above methods.

Bonus: Fit a Gaussian mixture model, select the optimal model and draw BIC and Silhouette plots.(Hint, you need to sample part of data or it could be very time consuming).