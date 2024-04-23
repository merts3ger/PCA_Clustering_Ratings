# PCA_Clustering_Ratings 

This project analyzes user preferences by clustering the average [ratings given by Google users](https://archive.ics.uci.edu/ml/datasets/Tarvel+Review+Ratings#) in their reviews of various attractions.    
The clustering algorithms experimented with are **k-Means** and Hierarchical Agglomerative Clustering (**HAC**), with a key focus on the application of Principal Component Analysis (**PCA**).      
    
* Within exploratory data analysis, feature distributions and descriptive statistics are examined to understand the data's underlying structure.     
* The optimal number of clusters is investigated by computing and plotting silhouette scores, utilizing the elbow point method with a KneeLocator for k-Means, and experimenting with dendrogram cuts for HAC.      
* PCA is used to collapse the high-dimensional original data (24 features) into a more manageable number of principal components. Upon plotting the individual and cumulative explained variance, it was determined that reducing the dataset to 10 principal components retains approximately 70% of the original dataset's information, achieving a compromise between simplification of the dataset and information loss.       
* Finally, the resulting clusters are visualized in 2D, compared and interpreted.      
