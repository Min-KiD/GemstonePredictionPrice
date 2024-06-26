# Gemstone Prediction Price

This is our project in machine learning subject in HUST uni

About the project: we focus on predicting the price of gemstones based on some attributes 

Learn more about the dataset: https://www.kaggle.com/competitions/playground-series-s3e8/data, `train.csv` is used for training, and `test.csv` is used for prediction and then submitted to kaggle for final result

- Open and read the file `ML-Project-Report(Gemstone).pdf` which is a brief report of our work 
- Open and read the file `GemstoneProject.ipynb` in src path for detail of our work
- Open and read the file `Experiment.ipynb` in src path for testing the hyper-parameter in the model or preprocessing part, trying the ideal we have with datasets, and see if you can do better, the coding for Optuna is at the bottom. You can also try to make your parameter or take the parameter we have tuned to put in there for the submission

Run file `.ipynb` by Jupyter notebook 

Detail description: EDA, feature engineering, data wrangling, and model training using machine learning models such as XGB, Gradient Boosting, Decision Tree, Random Forest, Linear, Ridge, Lasso, and ElasticNet are some of the tasks involved. The models are then fine-tuned using randomized, grid, and Bayes searches to determine the optimal hyperparameter model. I also create a model of myself using the ensemble approach, which combines the strongest models to provide a proportionate result that I believe will work best. Additionally, I attempt to employ autoML tools like H2O, which creates an end-to-end model combination, and Optuna, which provides hyper-parameter tweaking based on a heuristic approach.
