# Ames Housing Data 

1. Creating and iteratively refining a regression model
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process

The Ames Housing Dataset is a exceptionally detailed and robust dataset that has a very large number of columns.


## The Modeling Process

1. The train dataset has all of the columns that I need to generate and refine models. The test dataset has all of those columns except for the target that I am trying to predict in my Regression model.
2. Generate your regression model using the training data. We expect that within this process, you'll be making use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
3. Predict the values for your target column in the test dataset and submit your predictions to Kaggle to see how your model does against unknown data.

Models used:
Lasso
Ridge
ElasticNet
K Nearest Neighbors
