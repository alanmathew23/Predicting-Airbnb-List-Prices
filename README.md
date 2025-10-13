# Predicting-Airbnb-List-Prices
## Overview
This project demonstrates predicting Airbnb listing prices using LightGBM framework with K-fold cross-validation.<br>
It involves dataset loading, preprocessing, handling missing values, model training and generating predictions.
## Dataset
There were two datasets provided ``` train.csv ```  and ``` test.csv ``` <br>
The code attempts to load these files from multiple common locations. Update the file paths if necessary.

The target variable is logprice and there may be an id column.

## Usage 
Place ``` train.csv``` (required) and ``` test.csv``` (optional for final prediction) in one of the expected file paths or modify the trainpaths / testpaths lists in the notebook to match your directory structure.

Run the notebook in order.

Review the cross-validation RMSE output for model evaluation.

If ```test.csv``` is provided, a ```submission.csv``` file with predictions will be saved.

## Dependencies
``` pip install numpy pandas scikit-learn lightgbm ```

## Final Output 
The final output is present in the ``` submission.csv ``` file after the jupyter notebook is run.<br>
The ``` submission.csv ``` file will contain two columns target id and log(prices).