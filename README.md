# Credit Card Default Prediction

## Project Overview
Credit card default is a key issue for banks as it affects risk management and lending decisions. This project uses the [UCI Default of Credit Card Clients dataset](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset/data), which contains information on 30,000 credit card holders in Taiwan from 2005. The goal is to build a predictive model for credit card default through data cleaning, exploratory analysis, feature engineering, feature selection, and supervised machine learning.

## Models Tested
- LightGBM Classifier  
- CatBoost Classifier  
- Random Forest Classifier  
- Logistic Regression  
- K-Nearest Neighbors  

## Results
| Model                | Accuracy | Macro Avg F1 |
|-----------------------|----------|----------|
| Random Forest         | 0.780    | 0.694    |
| CatBoost              | 0.761    | 0.689    |
| LightGBM              | 0.754    | 0.682    |
| Logistic Regression   | 0.703    | 0.639    |
| KNN                   | 0.777    | 0.520    |


## Conclusion
Ensemble models (Random Forest, CatBoost, LightGBM) performed best overall. Logistic Regression and KNN did not perform as well, especially with the class imbalance in the dataset. With stronger preprocessing and feature engineering, the results could likely be improved.

## How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/r0nYang/Machine-Learning-for-Credit-Risk-Prediction.git
   cd Machine-Learning-for-Credit-Risk-Prediction
2. Open the notebook (`.ipynb`) using Jupyter Lab, VS Code, or any other environment that supports Jupyter notebooks.
