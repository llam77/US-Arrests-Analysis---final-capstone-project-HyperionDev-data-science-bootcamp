# usarrests_analysis

## Description

This project analyses crime data in the United States from 1973 to 1974 using clustering algorithms.

The UsArrests dataset contains statistics on violent crime and arrests for each of the 50 US states.
The variables included in the dataset are Murder, Assault, UrbanPop and Rape.

The main objective of the project is to use unsupervised learning techniques to gain insight into any patterns in the data.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Analysis](#analysis)
* [Results](#results)

## Installation<a name="installation"></a>

Use the package manager pip to install required packages.
![image](https://user-images.githubusercontent.com/67997413/220016690-148c2760-7316-4555-bc49-ca6221722cad.png)

## Usage<a name="usage"></a>

The project can be run in any environment that supports Python 3.x.
It is recommended that you use Jupyter Notebook to open the 'USArrests.ipynb' file to run the project.

Before running the project, download the 'UsArrests.csv' file and save it in the same directory as the 'USArrests.ipynb' file.
Then, run the cells in the notebook in order.

![image](https://user-images.githubusercontent.com/67997413/220017349-3a497c51-c952-452b-bd9f-4c6f7674a1e4.png)
![image](https://user-images.githubusercontent.com/67997413/220017706-427fdba8-35ac-45ea-a1b0-f4ef734f7ece.png)
![image](https://user-images.githubusercontent.com/67997413/220017823-6677b753-258f-4366-95b5-2080348c6891.png)


## Analysis<a name="analysis"></a>

The project includes the following steps:

1. Load the dataset
2. Check the statistics of the dataset
3. Check for missing values
4. Check the distribution of the observations for each feature
5. Perform a correlation analysis
6. Perform Principal Component Analysis (PCA)
7. Perform KMeans clustering
8. Perform Hierarchical clustering

## Results<a name="results"></a>

The PCA analysis revealed that Assault was the most important feature in the 
first principal component while UrbanPop was the most important feature in the second principal component.
KMeans clustering identified 3 clusters which highlighted states that had the highest crime rates in the dataset.
The hierarchical clustering analysis confirmed the results of KMeans clustering.
