# Machine Learning Engineering
# Supervised Learning

## Project Overview:
In this project, I applied  Supervised Learning algorithms and machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. I first explored the data to obtain important features and descriptive statistics about the dataset. Next, I properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. Then I analyzed performance graphs for a learning algorithm with varying parameters and training set sizes throgh grid search technique. This enabled me to pick the optimal model to predict a a housing prices of boston dataset.


## dataset:
The dataset for this project originates from the UCI Machine Learning Repository. The Boston housing data was collected in 1978 and each of the 506 entries represent aggregated data about 14 features for homes from various suburbs in Boston, Massachusetts. 
16 data points have an 'MEDV' value of 50.0. These data points likely contain missing or censored values and have been removed.
1 data point has an 'RM' value of 8.78. This data point can be considered an outlier and has been removed.
The features 'RM', 'LSTAT', 'PTRATIO', and 'MEDV' are essential. The remaining non-relevant features have been excluded.
The feature 'MEDV' has been multiplicatively scaled to account for 35 years of market inflation.

The modified Boston housing dataset consists of 490 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the UCI Machine Learning Repository.

### Features

RM: average number of rooms per dwelling
LSTAT: percentage of population considered lower status
PTRATIO: pupil-student ratio by town
Target Variable 4. MEDV: median value of owner-occupied homes
