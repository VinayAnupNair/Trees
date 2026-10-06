# CS 4372 - Tree Model Analysis

Vinay Nair  
NetID: van220003

## GitHUb Repository
https://github.com/VinayAnupNair/LinearRegression

## Dataset

UCI Heart Disease Dataset (Cleveland subset)  
Dataset ID: 45

The dataset is loaded directly using the ucimlrepo Python package. No local dataset file is required.

## Requirements

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- ucimlrepo
- xgboost

## Running the Code

1. Open the submitted .ipynb file in Google Colab or Jupyter Notebook.
2. Install the required packages if they are not already installed. In a notebook cell, run:

   ```python
   %pip install pandas numpy matplotlib seaborn scikit-learn ucimlrepo xgboost
   ```

3. Run all notebook cells from top to bottom.
4. The Heart Disease dataset will automatically be downloaded through ucimlrepo. An internet connection is required.
5. The notebook performs preprocessing, exploratory analysis, feature selection, model training, hyperparameter tuning, and evaluation.

## Models

- Decision Tree Classifier
- Random Forest Classifier
- AdaBoost Classifier
- XGBoost Classifier

## Notes

- The dataset is not included with the submission because it is retrieved directly through ucimlrepo.
- The target is converted into 0 (no heart disease) and 1 (heart disease present).
- random_state=42 is used where applicable for reproducibility.
- Hyperparameter tuning uses five-fold stratified cross-validation.
- Grid searches may take several minutes to finish.
