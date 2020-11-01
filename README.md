# Boston-housing-prediction
Predicts the price of houses in Boston using a machine learning algorithm called Linear Regression. And this is my first machine learning project.

### Dataset:
The proposed algorithm evaluated using Boston Housing dataset taken from kaggle.The Boston data frame has 506 rows and 14 columns.

Data is collected from website. https://www.kaggle.com/c/boston-housing
### Software Requirements:
         Operating System : Windows 7
         Development Kit : Python3.0, Jupyter Notebook, Anaconda
### Methodology:
After importing the dataset, we have to analyze the dataset, to check the shape of the data, check the target variable (median value), check the data type of features and the descriptive statistics of the data.

After analyze the dataset we have to convert the categorical variable into numeric because the machine learning model work with only numeric features. then clean the duplictes and null values. In this dataset doesn't contain any categorical features and null values.

Before making the model we apply the Normalizer scalar. Scaling technique is useful as features should have the same order of magnitude for the algorithm to work properly.Then making model using Linear regression algorithm.

After making the model, we have to check the performance of the model using R2 score, MAE, MSE and root MSE.
