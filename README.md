
# Machine Learning and Statistics Assessment 2019

## Title: An analysis of Boston House Prices in Jupyter Notebook.

The actual file to review is called **Boston House Prices.ipynb** and is contained in this Repository.

The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. There are 506 line items and 13 attributes (excluding price). The aim here is to provide a detailed description of the dataset and an investigation into the House Price prediction drivers contained therein.

The following describes the dataset columns:

+ CRIM - per capita crime rate by town
+ ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
+ INDUS - proportion of non-retail business acres per town.
+ CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
+ NOX - nitric oxides concentration (parts per 10 million)
+ RM - average number of rooms per dwelling
+ AGE - proportion of owner-occupied units built prior to 1940
+ DIS - weighted distances to five Boston employment centres
+ RAD - index of accessibility to radial highways
+ TAX - full-value property-tax rate per 10,000
+ PTRATIO pupil-teacher ratio by town.
+ B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
+ LSTAT - % lower status of the population.
+ MEDV - Median value of owner-occupied homes in 1000's.

## Packages Required
To review this assignment one is required and access to [Jupyter](https://jupyter.org/) Notebooks
[Python](https://www.python.org/) Programming language was used as the foundation to all analysis. 

The libraries below were also imported to Python to fully utilse most useful available features.
These are used for both analysis and data visualisation.

- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [skikit-learn](https://scikit-learn.org/stable/index.html0)
- [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html)
- [seaborn](https://seaborn.pydata.org/)

## Reviewing the notebook
Template code is provided in the Boston House Prices.ipynb notebook file. 

The Jupyter Notebook is broken down into 3 main sections.

1. Descriptive Statistics contains:
  - A summary of the data set and its key features
  - Visualisations of the dataset to provide insights for further analysis
    - Histograms, Scatterplots, Boxplots
    - Key features of the datset identified
    
2. Inferential Statistics
  - A deeper dive into the dataset using Regression, Correlation, T-Tests and ANOVA
  
3. Creating a model to predict House Prices using scipy, Ski learn
  - A Neural Network was used to import and Train the Model and adjusted to minimal MSE
  - Data split into training and test elements
  - Use of Preprocessing, Scaling and Standardisation techniques
  - the addition of input layers, measures and use of Whitening to develop the model
  
In Backup are the Histograms, scatter plots referred to throughout the file as well as all referenced material used in support.


