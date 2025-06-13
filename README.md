# Heart-Disease-Prediction
This project aims to predict the likelihood of a heart attack based on an individual's health data using machine learning techniques. The goal is to identify patterns in medical features that may indicate increased risk, thereby supporting early intervention and prevention.


## Key Steps
* Exploratory Data Analysis (EDA): Initial analyses were performed to understand the dataset.

* Handling Missing Values and Data Imbalance: Missing and imbalanced values in the dataset were cleaned to ensure the model works more accurately.

* Feature Engineering and Encoding: Categorical data was converted into numerical format to prepare it for machine learning algorithms.

* Model Training and Evaluation: Powerful models like XGBoost were used to train a classification model for predicting heart attack risk, and its performance was evaluated using various metrics.

## Model Performance
The trained XGBoost model predicts heart attack risk with 93% accuracy. The SMOTE (Synthetic Minority Over-sampling Technique) algorithm was used to address data imbalance and improve the model's accuracy.

## Potential Use Cases
This model could be highly beneficial for healthcare providers in identifying high-risk patients early on, enabling them to take preventive actions.

## How to Run the Project
1. Clone this repository to your local machine:
```
git clone https://github.com/lightlessy/Heart-Disease-Prediction.git
```
2. Navigate into the project directory:
```
cd Heart-Disease-Prediction
```
3. Install the necessary Python libraries (these are usually pre-installed in Kaggle environments; install them if running locally):
```python
pip install pandas numpy scikit-learn matplotlib seaborn xgboost imbalanced-learn
```
4. Open the Notebooks/heartdisease.ipynb file with Jupyter Notebook or JupyterLab and run all cells.
