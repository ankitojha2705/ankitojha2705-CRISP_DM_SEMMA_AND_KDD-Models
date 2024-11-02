# Customer Churn Prediction Project

This project employs three different data mining methodologies—CRISP-DM, KDD, and SEMMA—on distinct datasets from Kaggle to solve customer churn and fraud detection problems. The process includes data understanding, preparation, model training, evaluation, and insights for deployment.

- Medium Article for CRISP-DM https://medium.com/@ankit2705ojha/data-mining-assignment-using-the-crisp-dm-methodology-bbb724a4263b
- Medium Article for KDD https://medium.com/@ankit2705ojha/data-mining-assignment-using-the-kdd-methodology-52e516c1c3cf
- Medium Article for SEMMA https://medium.com/@ankit2705ojha/data-mining-assignment-using-the-semma-methodology-2648cf479de6


## Methodologies & Datasets

### 1. CRISP-DM Methodology
- **Dataset**: Customer Churn dataset (Kaggle)
- **Steps**:
  - **Business Understanding**: Defined the goal as predicting customer churn to assist in customer retention strategies.
  - **Data Understanding**: Explored data distributions, correlations, and visualizations to identify important features.
  - **Data Preparation**: Managed missing values, encoded categorical variables, scaled features, and engineered new features.
  - **Modeling**: Trained Logistic Regression, Random Forest, and XGBoost models. Performed hyperparameter tuning for optimization.
  - **Evaluation**: Evaluated models using Accuracy, Precision, Recall, and F1 Score. Random Forest was the best model.
  - **Deployment**: Outlined deployment strategies and potential real-world applications.

### 2. KDD Methodology
- **Dataset**: Credit Card Fraud Detection dataset (Kaggle)
- **Steps**:
  - **Data Selection**: Choose relevant features and filter uninformative data for efficient churn prediction.
  - **Preprocessing**: Cleaned data, handled class imbalances using SMOTE, and transformed features.
  - **Data Transformation**: Standardized the dataset through feature scaling and encoding.
  - **Data Mining**: Applied Random Forest and XGBoost models, using Grid Search for hyperparameter tuning.
  - **Evaluation**: Analyzed model metrics, with a focus on improving accuracy and robustness.

### 3. SEMMA Methodology
- **Dataset**: Telco Customer Churn dataset (Kaggle)
- **Steps**:
  - **Sample**: Split the data into training and testing sets for model assessment.
  - **Explore**: Conducted EDA, visualizing distributions and feature relationships.
  - **Modify**: Addressed missing values, encoded categorical data, scaled features, and engineered new variables.
  - **Model**: Developed and tuned models (Logistic Regression, Random Forest, XGBoost) to improve performance.
  - **Assess**: Compared metrics across models, with Random Forest delivering the best F1 Score.

## Key Results
- **CRISP-DM**: Achieved a strong F1 Score with a tuned Random Forest model on the Telco dataset.
- **KDD**: Improved model performance for fraud detection through effective class balancing and feature selection.
- **SEMMA**: Enhanced model accuracy and interpretability with thorough EDA and feature engineering.

## Future Work
- Explore deep learning models for capturing complex patterns.
- Use AutoML tools for more efficient hyperparameter tuning.
- Implement real-time data pipelines for continuous model improvement.

## Acknowledgments
- **Kaggle**: Thanks to Kaggle for the datasets that enabled comprehensive data mining and analysis for this project.

---
