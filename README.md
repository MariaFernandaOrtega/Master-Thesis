# Master thesis: Corruption Trajectories in 133 Countries: A Time Series Clustering Study from 2000 to 2022


## About

This repository contains the research work for a study that investigates the clustering of political, executive, legislative, and judicial corruption in 133 countries from 2000 to 2022, using time-series clustering techniques. The clustering was achieved through methods such as Time Series K-means with different distance metrics (Euclidean, DTW, Soft-DTW) and Kernel K-means. Model evaluations were conducted using the Silhouette Score and Davies-Bouldin Score. In addition, the study explores the correlation between the absence of corruption in these clusters and key socio-political and economic variables. 


## How to Use This Repository
- To review the data, navigate to `/data`. All sources where obtain from international organizations that provide free acess to their data.
- To review the metada files that detail the structure, descriptions of datasets used, see  `/Metadata`. For the specific variables used in the clustering models see, `/Code_book`. 
- For  the preprocessing code (e.g. import data, clean data, and get the final dataset), check `data_preprocessing.qmd`.
- For the code for the models implementation and evaluation, check `model_code.ipynb`.
- To see the visual results, explore the `/figures` directory.
- To read the paper, view `thesis-written-part.pdf`.


## Contributions
This work is part of the master thesis of Maria Fernanda Ortega, for the Master of Data Science for Public Policy at the Hertie School.

## Bibliography used for the code implementation

--- 
