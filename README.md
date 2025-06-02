# Customer Churn Prediction

This project predicts customer churn using a telecom dataset with various customer attributes.

## Dataset
- Telecom customer data with features like contract type, tenure, monthly charges, and churn label (yes/no).

## What I Did
- Handled class imbalance using **SMOTE** to generate synthetic samples of the minority class (churners).
- Tested machine learning models including **Random Forest** and **XGBoost** on resampled data.
- Applied **cross-validation** to assess model performance reliably.
- Evaluated models using accuracy, precision, recall, F1-score, and confusion matrix.

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
