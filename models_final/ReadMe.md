# Content: Model Evaluation and Validation
## Project: Predicting Boston Housing Prices

## Project Overview
In this project, we will apply basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. we will first explore the data to obtain important features and descriptive statistics about the dataset. Next, we will properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. we will then analyze performance graphs for a learning algorithm with varying parameters and training set sizes. This will enable us to pick the optimal model that best generalizes for unseen data. Finally, we will test this optimal model on a new sample and compare the predicted selling price to our statistics.

## Project Highlights

Things done as part of  completing this project:

- Using NumPy to investigate the latent features of a dataset.
- Analyzing various learning performance plots for variance and bias.
- Determining the best-guess model for predictions from unseen data.
- Evaluating a model's performance on unseen data using previous data.

## Description
The Housing market is highly competitive, and we want to be the best real estate agent in the area. To compete with the peers, we decide to leverage a few basic machine learning concepts to assist us and a client with finding the best selling price for their home. The dataset contains  various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Our task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for your clients\' homes.

## Software and Libraries
This project uses the following software and Python libraries:

- [Python](https://www.python.org/download/releases/3.0/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

## Main Project Files


This project contains three files:

- `boston_housing.ipynb`: Python file containing the prediction code. 
- `housing.csv`: The project dataset.
- `visuals.py`: This Python script provides supplementary visualizations for the project. 

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
