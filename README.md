# Clustering-techniques
BBC News Clustering Project
Overview:
This project involves clustering news articles from the BBC News dataset using various techniques. The goal is to organize articles into coherent groups based on their content. The dataset comprises 2225 articles spanning five themes: business, entertainment, politics, sport, and tech. For simplicity, only the title and content of each article are considered.

Project Structure:

Text Preprocessing:
Tokenization: Breaking down text into smaller units.
Stop Words Removal: Eliminating common words for streamlined processing.
Lemmatization and Stemming: Converting words to their base or dictionary form.
Vectorization: Transforming text into a matrix of TF-IDF features for clustering.


Clustering Algorithms:
K-means Clustering: Segregating news articles into 5 distinct clusters.
DBSCAN Clustering: Implementing the DBSCAN clustering algorithm.
Gaussian Mixture Model (GMM) Clustering: Allocating news articles into 5 clusters using GMM.
Agglomerative Clustering: Administering Agglomerative Clustering to form 5 coherent clusters.


Questions Addressed:
Reporting the number of articles in each cluster for each method.
Illustrating clusters through PCA dimensionality reduction.
Implementing DBSCAN's K-distance Graph to estimate optimal eps.
Using WCSS to identify the ideal number of clusters for K-means.
