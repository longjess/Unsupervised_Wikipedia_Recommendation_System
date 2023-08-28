# Unsupervised_Wikipedia_Recommendation_System
This project aims to create a system for recommending articles related to a given Wikipedia article, based on tf-idf scores. Using item-based recommendation, k-means clustering, hierarchical agglomerative clustering, and deep embedded clustering, the system find articles that are similar to a given article and return list ranked in terms of closeness to the original article.

This was my final project for Stanford's STATS315B Modern Applied Statistics II: Learning course in Spring 2023.

This repository includes:
* clustering_exploration.ipynb: code for exploring the characteristics of clustering methods, used for selecting the final clusters
* recommendation_system.ipynb: code for analysing the final clusters and for the recommendation system
* STATS315B_Project_Report.pdf: report including the goals of the project, the methods used, the selection of the final clusters, and an analysis of the recommendation results
* Dataset: includes tf-idf scores for a selection of Wikipedia articles, and a corresponding dictionary
* Output: includes plots and tables for heterogenity scores, silhouette scores, and cluster sizes for various clustering methods

For the deep embedded clustering I used the package ptdec: https://github.com/vlukiyanov/pt-dec
