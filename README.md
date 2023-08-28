# Unsupervised_Wikipedia_Recommendation_System
This project aims to create a system for recommending articles related to a given Wikipedia article, based on tf-idf scores. Using item-based recommendation, k-means clustering, hierarchical agglomerative clustering, and deep embedded clustering, the system find articles that are similar to a given article and return list ranked in terms of closeness to the original article.

This was my final project for Stanford's STATS315B Modern Applied Statistics II: Learning course in Spring 2023.

The repository includes:
* clustering_exploration.ipynb: code for determining the number of clusters to use for each clustering method
* recommendation_system.ipynb: code for analyzing the properties of the final clusters, and for producing recommendations
* The dataset, containing tf-idf scores for a selection of articles and a dictionary
* The project report, describing the goals of the project, the methods used, the means by which the final clusters were determined, and an analysis of the recommendations given by each method.
* Output, consisting of plots and tables for heterogenity, silhouette score, and cluster size for various clustering methods

For deep embedded clustering I used the Python package ptdec: https://github.com/vlukiyanov/pt-dec




