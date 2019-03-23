# Machine learning (Model evaluation and validation)
## Boston-house-project
Predicting Boston House Price

### Project Overview
The Boston housing market is highly competitive, and you want to be the best real estate agent in the area. To compete with your peers, you decide to leverage a few basic machine learning concepts to assist you and a client with finding the best selling price for their home. Luckily, you’ve come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Your task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for your clients' homes.

### Project Highlights
This project is designed to get you acquainted with the many techniques for training, testing, evaluating, and optimizing models, available in sklearn.

Things i have learned by completing this project:

- How to explore data and observe features.
- How to train and test models.
- How to identify potential problems, such as errors due to bias or variance.
- How to apply techniques to improve the model, such as cross-validation and grid search.

### Data Set
The dataset for this project originates from the UCI Machine Learning Repository. The Boston housing data was collected in 1978 and each of the 506 entries represent aggregated data about 14 features for homes from various suburbs in Boston, Massachusetts. For the purposes of this project, the following preprocessing steps have been made to the dataset:

16 data points have an 'MEDV' value of 50.0. These data points likely contain missing or censored values and have been removed.
1 data point has an 'RM' value of 8.78. This data point can be considered an outlier and has been removed.
The features 'RM', 'LSTAT', 'PTRATIO', and 'MEDV' are essential. The remaining non-relevant features have been excluded.
The feature 'MEDV' has been multiplicatively scaled to account for 35 years of market inflation.


### samples of predicted selling prices:
Predicted selling price for Client 1's home: $403,025.00

Predicted selling price for Client 2's home: $237,478.72

Predicted selling price for Client 3's home: $931,636.36
