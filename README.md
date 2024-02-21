# Mall Customer Segmentation using Clustering

## About the Project
This project aims to demonstrate customer segmentation, also known as market basket analysis, using an unsupervised machine learning technique - mainly the KMeans Clustering Algorithm. The purpose is to help understand customer behavior in a supermarket mall setting, facilitating targeted marketing strategies by segmenting customers based on their spending patterns and demographics.

## Dataset Context
The dataset is crafted for educational purposes, focusing on the learning aspects of customer segmentation concepts. It simulates a scenario where a supermarket mall collects basic data on its customers through membership cards. The data includes Customer ID, age, gender, annual income, and spending score, which is a metric assigned by the mall based on customer behavior and purchasing data.

### Data Source
The dataset used in this project is inspired by the Machine Learning A-Z course on Udemy and can be found [here](https://github.com/SteffiPeTaffy/machineLearningAZ/blob/master/Machine%20Learning%20A-Z%20Template%20Folder/Part%204%20-%20Clustering/Section%2025%20-%20Hierarchical%20Clustering/Mall_Customers.csv).

## Problem Statement
The main objective is to segment mall customers to identify target groups that can be approached with tailored marketing strategies, enhancing the efficiency of marketing efforts and potentially increasing sales.

## Methodology
The analysis begins with data preprocessing, including cleaning and standardization, to make the dataset suitable for clustering. The KMeans algorithm is then applied to segment customers into distinct groups based on their attributes. The process involves:

- Exploratory Data Analysis (EDA) to understand the dataset's characteristics.
- Using the Elbow Method and Silhouette Score to determine the optimal number of clusters for KMeans
- Applying PCA (Principal Component Analysis) for dimensionality reduction to visualize the clusters.
- Comparing KMeans with other clustering algorithms like Affinity Propagation, Mean-Shift, Spectral Clustering, Agglomerative Clustering, DBSCAN, OPTICS, Gaussian Mixtures, and BIRCH to evaluate their effectiveness in customer segmentation.

## Results and Discussion
The analysis revealed that while KMeans is a popular choice for clustering, other methods like Affinity Propagation showed promising results in this context. The project demonstrates the importance of comparing different algorithms to find the most suitable one for specific datasets and objectives.

## Conclusion and Future Work
This case study highlights the potential of using unsupervised learning techniques for customer segmentation in the retail industry. Future work could explore more advanced techniques and hyperparameter tuning to refine the segmentation further and potentially incorporate additional data sources for deeper insights.

## Acknowledgements
This project was inspired by the Machine Learning A-Z course on Udemy. It is intended for educational purposes and to share knowledge with others interested in machine learning and customer segmentation.
