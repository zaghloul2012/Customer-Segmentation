
# Customer Segmentation

## Introduction
The idea of this project is to address the issue of customer segmentation into discrete groups that share similar characteristics and needs. 

The goal of this project is to perform customer segmentation using basic data about customers like Customer ID, age, gender, annual income, and spending score in order to identify target customers and develop marketing strategies to appeal to their needs and preferences.

## Dataset
The dataset contains information about customers of a supermarket mall, including their age, gender, annual income, and spending score. This dataset can be used for customer segmentation analysis and to develop targeted marketing strategies.

Data can be downloaded from [here](https://www.kaggle.com/datasets/dev0914sharma/customer-clustering?select=segmentation+data.csv)


## Model Development 
This project aims to develop and implement various clustering models to categorize the customers into discrete groups based on the available features in the dataset.

The first step in this project was to clean, organize, and transform the data into a format that is acceptable by machine learning models. The data cleaning process involved removing missing values, removing outliers, and checking for data consistency. The transformed dataset was then used for model development.

Several clustering models were developed and evaluated on the transformed dataset. The following are the models developed:

1. K-means: K-means clustering is a technique for finding groups of similar data points in a dataset. It works by partitioning the data into a predefined number of clusters, each with a center called a centroid. The algorithm assigns each data point to the cluster whose centroid is closest to it, and then updates the centroids based on the new assignments. This process is repeated until the clusters do not change significantly.

2. Hierarchical clustering: Hierarchical clustering is a method of cluster analysis that seeks to build a hierarchy of clusters based on the dissimilarity between data points. 


## Results
The two models we used (K-means , Hierarchical clustering) to segment the customers showed similar results, with only minor differences in some clusters.

To evaluate which model is more suitable for our marketing strategy, we need to consider other factors, such as the business objectives, the customer feedback, and the expected return on investment.

### K-means Clustering Results
![K-means results](/kmeans_results.png "K-means Results")

### Hierarchical Clustering Results
![Hierarchical results](/hierarchical_results.png "Hierarchical Results")



## Acknowledgements

 - [Customer Segmentation Dataset](https://www.kaggle.com/datasets/dev0914sharma/customer-clustering?select=segmentation+data.csv)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Feedback

If you have any feedback, please reach out to us at youssef.zaghloul@ejust.edu.eg

