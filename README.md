This project focuses on segmenting credit card customers based on their usage patterns to uncover meaningful customer groups, which can be useful for targeted marketing and better customer service.

Objective
The goal of this analysis is to group customers into clusters based on various financial attributes, such as balance, purchases, credit limit, and payments. This segmentation can help in identifying unique customer behaviors and designing personalized offerings.

Steps Followed
Data Loading and Preprocessing

Loaded a credit card customer dataset and removed the CUST_ID column, as it’s irrelevant to clustering.
Handled missing values by filling them with median values of respective columns.
Standardized the features to normalize different financial metrics.
Elbow Method for Optimal Clusters

Used the Elbow Method to determine an optimal number of clusters by plotting Within-Cluster Sum of Squares (WCSS) against different values of 𝑘.
Based on the elbow point, chose an optimal cluster count for further analysis.

K-Means Clustering
Applied K-Means clustering with the chosen number of clusters, adding the cluster labels to the dataset.
Analyzed the cluster centers to understand the unique characteristics of each segment.

Cluster Visualization
Visualized clusters using 2D scatter plots and pair plots to observe relationships between key financial features.
Created a 3D scatter plot to gain additional insights into cluster distribution across multiple dimensions.

Cluster Validation
Evaluated clustering performance using Silhouette Score and Davies-Bouldin Index to assess cluster cohesion and separation.

Cluster Analysis
Generated summary statistics and box plots to examine the distribution of features within each cluster.
Created a heatmap of cluster centers to compare the average values of each feature across clusters, aiding interpretation.

Results
The analysis provides a basis for interpreting different customer segments based on spending behavior, credit usage, and payment patterns. These insights can assist in designing targeted marketing strategies and personalized credit card offers.
