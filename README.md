# Master thesis: Corruption Trajectories in 133 Countries: A Time Series Clustering Study from 2000 to 2022


## About

This repository contains the research work for a study that investigates the clustering of political, executive, legislative, and judicial corruption in 133 countries from 2000 to 2022, using time-series clustering techniques. The clustering was achieved through methods such as Time Series K-means with different distance metrics (Euclidean, DTW, Soft-DTW) and Kernel K-means. Model evaluations were conducted using the Silhouette Score and Davies-Bouldin Score. In addition, the study explores the correlation between the absence of corruption in these clusters and key socio-political and economic variables. 


## How to Use This Repository
- To review the data, navigate to `/data`. All sources where obtain from international organizations that provide free acess to their data.
  - The data from the V-Dem Institute is too large to be uploaded to this repository, but it is essential for the model implementation. Access it here: https://v-dem.net/data/the-v-dem-dataset/
- To review the metada files that detail the structure, descriptions of datasets used, see  `/Metadata`. For the specific variables used in the clustering models see, `/Code_book`. 
- For  the preprocessing code (e.g. import data, clean data, and get the final dataset), check `data_preprocessing.qmd`.
- For the code for the models implementation and evaluation, check `model_code.ipynb`.
- To see the visual results, explore the `/figures` directory.
- To read the paper, view `thesis-written-part.pdf`.


## Contributions
This work is part of the master thesis of Maria Fernanda Ortega, for the Master of Data Science for Public Policy at the Hertie School.

## Bibliography used for the code implementation
Amidon, A. (n.d.). How to Apply K-means Clustering to Time Series Data. Towards Data Science. Retrieved 26 March 2024, from https://towardsdatascience.com/how-to-apply-k-means-clustering-to-time-series-data-28d04a8f7da3
Cerliani, M. (2023, January 31). PCA for Multivariate Time Series: Forecasting Dynamic High-Dimensional Data. Medium. https://towardsdatascience.com/pca-for-multivariate-time-series-forecasting-dynamic-high-dimensional-data-ab050a19e8db
Ecosystem (LEDU), E. (2018, September 12). Understanding K-means Clustering in Machine Learning. Medium. https://towardsdatascience.com/understanding-k-means-clustering-in-machine-learning-6a6e67336aa1
Graff, V. (2023, April 13). Dimension Reduction: Facing the Curse of Dimensionality. Medium. https://towardsdatascience.com/dimension-reduction-facing-the-curse-of-dimensionality-63a743e4b199
Heka.ai. (2022, June 9). Time series clustering. Medium. https://heka-ai.medium.com/time-series-clustering-b84bcaaa63ac
Introduction to Time Series Clustering. (n.d.). Retrieved 26 March 2024, from https://kaggle.com/code/izzettunc/introduction-to-time-series-clustering
Saleh, H. (2023, December 21). Unveiling Patterns in Time: A Guide to Time Series Clustering with tslearn. Medium. https://levelup.gitconnected.com/unveiling-patterns-in-time-a-guide-to-time-series-clustering-with-tslearn-50a2ff305afe
Time Series Clustering—Tslearn 0.6.3 documentation. (n.d.-a). Retrieved 26 March 2024, from https://tslearn.readthedocs.io/en/stable/user_guide/clustering.html
Time Series Clustering—Tslearn 0.6.3 documentation. (n.d.-b). Retrieved 20 April 2024, from https://tslearn.readthedocs.io/en/stable/user_guide/clustering.html
Tousignant, P. (2023, January 16). Dynamic Factor Models in Python. Medium. https://medium.com/@philippetousignant/dynamic-factor-models-in-python-58d2d5252640


--- 
