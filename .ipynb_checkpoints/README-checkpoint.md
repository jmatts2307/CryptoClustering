# CryptoClustering

In this challenge, Python and unsupervised learning were used to analyze and predict whether cryptocurrencies are affected by 24-hour or 7-day price changes. Using K-Means clustering, this assignment groups cryptocurrencies based on their price movements and compares results before and after applying Principle Component Analysis (PCA) for optimization. 

Key Features:

Elbow Method to determine the optimal 'k' value.

K-Means Clustering on both scaled and PCA-reduced data.

Visualizations to compare clusters before and after reduction.


Technologies Used:

Python (pandas, sklearn, hvPlot, matplotlib), jupyter notebook.


Conclusion:

PCA successfully concentrated clusters while retaining the original structure.The optimal number of clusters remained the same which confirmed consistency. PCA data showed tighter groupings, suggesting that there were reductions in dimensionality, but still preserved key relationships. 
