# WHO-Life-Expectancy-Prediction
Predicting Life Expectancy of a  Country using various health and social-economic factors

## Dataset
This data-set related to life expectancy and  health factors for 193 countries has been collected from the  WHO data repository website and its corresponding economic data was collected from United Nation website. 

Details about the Dataset and Column Description can be found in https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who. 

Cleaned dataset can be found in https://www.kaggle.com/datasets/lashagoch/life-expectancy-who-updated/code

## Training

Dataset was split into 80% training set and 20% test set. Using Gridsearch with 5-fold cross validation, 5 models with different hyperparameters were tried. 

## Evaluation and Result

A variant of Random Forest came out top based on RMSE and R^2
