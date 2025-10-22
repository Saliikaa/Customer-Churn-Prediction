Customer Churn Prediction
Overview

    This project focuses on predicting customer churn for a telecom company using machine learning. The goal is to understand customer behavior, identify the main factors        that lead to churn, and build a model that can predict whether a customer is likely to leave.
    The entire workflow—from data preprocessing to model building and evaluation—is done in Google Colab.


Key Features

      Performed complete Exploratory Data Analysis (EDA) with visualizations using matplotlib and seaborn.

      Cleaned and prepared data by handling missing values and encoding categorical columns.

      Used the SMOTE technique to fix class imbalance in the target variable.

Trained and compared multiple models:

      Decision Tree Classifier

      Random Forest Classifier

      XGBoost Classifier

Evaluated performance using accuracy score, confusion matrix, and classification report.

Saved the final model with pickle for reuse and deployment.

Included a demo to predict churn for a single customer using the saved model and encoders.

Technologies Used

     Python 3

     Pandas, NumPy, Matplotlib, Seaborn

     Scikit-learn, XGBoost, Imbalanced-learn (SMOTE)

     FastAPI, Uvicorn (deployment-ready structure)

     Google Colab

Dataset

    File: WA_Fn-UseC_-Telco-Customer-Churn.csv
    This dataset contains telecom customer data with details such as demographics, services used, contract type, and churn status.

Workflow

    Mount Google Drive and load the dataset.

    Perform cleaning, type conversions, and feature inspection.

    Encode categorical variables using LabelEncoder and OneHotEncoder.

    Split data into training and testing sets.

    Apply SMOTE to balance classes.

    Train multiple models and evaluate them.

    Save the best-performing model (Random Forest).

    Test predictions on new, unseen data.

 Example  of Prediction

    For a new customer, the model gives an output like:

    Prediction: Churn
    Probability of Churn: 74.32%


Results

      Best model: Random Forest Classifier

      Accuracy: Around 85–90% (may vary slightly depending on random state and parameters)

Future Improvements

      Fine-tune hyperparameters to increase accuracy.

      Deploy the model as an API using FastAPI and Uvicorn.

     Build a web interface to make predictions interactiv


📫 Email: jamwalsalika@gmail.com
