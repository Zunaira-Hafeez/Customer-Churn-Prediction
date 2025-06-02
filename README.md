# Customer Churn Prediction

This project predicts customer churn using a telecom dataset with various customer attributes.

## Dataset
- Telecom customer data with features like contract type, tenure, monthly charges, and churn label (yes/no).
- URL = https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

## What I Did
- **Exploratory Data Analysis (EDA):** Analyzed the telecom dataset to understand feature distributions, missing values, and class imbalance.
- **Data Preprocessing:** Cleaned the data by handling missing values, encoding categorical variables using one-hot encoding, and scaling features where necessary.
- **Handled Class Imbalance:** Used **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the dataset by generating synthetic samples for the minority class (churners).
- **Modeling:** Trained and compared three machine learning models:
  - **Logistic Regression** as a baseline.
  - **Random Forest Classifier** for better handling of complex data patterns.
  - **XGBoost Classifier** for efficient gradient boosting and improved accuracy.
- **Model Evaluation:** Used **cross-validation** to assess model stability and evaluated performance on test data using accuracy, precision, recall, F1-score, and confusion matrix.

## Results
- Models achieved around **77-78% accuracy**.
- Although overall accuracy improved, recall for churners (minority class) remains moderate.
- Model tuning and feature engineering are suggested next steps to further improve performance.

## Future Work
- Hyperparameter tuning with GridSearchCV.
- Advanced resampling techniques like SMOTEENN.
- Feature selection and engineering.
- Focus on improving recall and F1-score for better churn detection.

## How to Use
1. Clone the repository.
2. Install required packages (e.g., scikit-learn, imblearn, xgboost).
3. Run the Jupyter notebook or Python scripts to train and evaluate models.
