# Crop Production Prediction
## Introduction

Predicting crop production from a small dataset with only three features. Just a proof of concept for demonstration purposes to a group of students. This is a sample of a real dataset. This dataset was choosen instead of the usual house price prediction that is normally used for regression problems.

## Project Overview
- Performed Exploratory Data Analysis
- Performed Preparation of Features for ML Models
- Tested and evaluated multiple algorithms (Metric: Mean Squared Error)
- Use GridSearch to optimize the best algorithms chosen from the step above

## Resources
- Python Version: 3.9.12
- Packages: Numpy, Pandas, Seaborn, Matplotlib, sklearn 

## Model Building
The following models were tested:

- LinearRegression (LR)
- XGBRegressor (LGBMR)
- SGDRegressor (SGD)
- KernelRidge (KR)
- GradientBoostingRegressor (GBR)
- SVR (SVR)

## Results
The following Mean Squared Errors were achieved:

- 'KR': 14349613.933233494,
-  'SGD': 14484732.29026102,
-  'LR': 14792778.634092111,
-  'SVR': 19307578.674022447,
-  'GBR': 24705437.750485,
-  'LGBMR': 30389624.50301913}

The above shows that we are way off with our prediction. Based on the data, I think I need more data to be able to get meaningful results.