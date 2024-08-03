## Predicting_Sale_Price
# Overview
This project aims to predict the sale price of bulldozers using machine learning techniques. It leverages historical sales data to build a model capable of accurately estimating the price of a bulldozer based on its features.

# Dataset
The dataset used for this project is obtained from Kaggle Bluebook for Bulldozers competition. It consists of three primary datasets:

* Train.csv: Contains historical sales data up to 2011.
* Valid.csv: Contains data from January 1, 2012 to April 30, 2012.
* Test.csv: Contains data from May 1, 2012 to November 2012.
# Data Preprocessing
The dataset undergoes several preprocessing steps, including:

* Handling missing values
* Feature engineering
* Exploratory data analysis
* Feature scaling
# Model Development
Various machine learning models are explored and evaluated, such as:

* Linear Regression
* Random Forest
The optimal model is selected based on performance metrics like Root Mean Squared Log Error (RMSLE).

# Evaluation
The model's performance is assessed using the RMSLE metric on the validation set.

# Dependencies
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
# Usage
* Clone the repository.
* Install the required dependencies using pip install -r requirements.txt.
* Run the Jupyter Notebook or Python script to train and evaluate the model.
