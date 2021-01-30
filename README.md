# Cryptocurrencies

Unsupervised learning model is different from supervised learning in that an unsupervised model provides unlabeled data that the algorithm understands by extracting features and patterns on its own. In a supervised leaning model, the algorithm learns on a labeled dataset, and helps predict outcomes for unforeseen data. In other words, supervised learning is used when we know what we are looking for or what the output should be. Unsupervised learning is used when we don’t know the question we are asking the data. 

In this module, we learned what unsupervised learning is used for, how to process data, how to cluster, how to reduce your dimensions, and how to reduce the principle components using PCA. Through the use of this knowledge, we will create an analysis for a client who is preparing to get into the cryptocurrency market.

## Results

The data that is initially given is not ideal so it was first processed to fit the machine learning models. Since there is no known output, unsupervised learning was used. To look at the difference cryptocurrencies, it was decided to use a clustering algorithm. 

Python was used as the tool for this analysis and divided into four parts: Processing the Data for PCA, reducing the data dimensions using PCA, clustering cryptocurrencies using K-means, and finally visualizing cryptocurrencies results.

The first visualization that was made was through the use of and elbow curve to determine the cluster count:
![](https://github.com/holleyvoegtle/Cryptocurrencies/blob/main/images/ElbowCurve.png)

Data was combined and a 3D-scatter plot was made with the PCA data and the clusters:
![](https://github.com/holleyvoegtle/Cryptocurrencies/blob/main/images/3D-Scatter%20plot.png)

Finally, a hvplot.scatter plot was created using x=Total Coins Mined and y=Total Coin Supply:
![](https://github.com/holleyvoegtle/Cryptocurrencies/blob/main/images/ScatterPlot.png)
