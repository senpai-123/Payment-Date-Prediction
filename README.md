# Payment-Date-Prediction
This project focuses on predicting payment delays using machine learning models. The Jupyter Notebook employs Python libraries such as pandas, seaborn, matplotlib, numpy, xgboost, and scikit-learn for data exploration, model training, and evaluation.

The dataset is manipulated to calculate the delay between the clear date and the due date, providing a crucial target variable for prediction. Exploratory data analysis involves understanding average delays across customers.

XGBoost is identified as the preferred model due to its superior performance in terms of accuracy, as indicated by the R2 score.

Hyperparameter Tuning
Grid search is conducted to fine-tune hyperparameters, enhancing the XGBoost model's predictive capabilities. The best hyperparameters are identified, and the model is retrained with these optimized settings.

Feature Engineering
Selected columns are identified for further analysis, including total open amount, customer payment terms, business code, customer number, and due term. The dataset is then prepared for model training.

Aging Bucket Classification
The model is applied to untouched data to predict average delay seconds, which is then converted into average delay days. An aging bucket classification is created to categorize delays into 0-15, 16-30, 46-60, and greater than 60 days.
