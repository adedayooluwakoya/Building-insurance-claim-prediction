# Building Insurance Claim Prediction

## Project Overview
The goal of this project is to **predict whether a building will have an insurance claim** during its insured period based on building characteristics.  
The target variable, `Claim`, is binary:
- `1` → at least one claim
- `0` → no claim

## Dataset
The dataset contains information about buildings such as:
- Building dimensions
- Premium amount
- Sum insured
- Location, building type, etc.

> Note: Dataset is not included due to size/privacy, but preprocessing steps are demonstrated in the notebook.

## Methodology
1. **Exploratory Data Analysis (EDA)**
   - Understand feature distributions
   - Identify skewed numeric features
2. **Data Preprocessing**
   - Encoding categorical variables (LabelEncoder)
   - Scaling numeric features (StandardScaler)
   - Handling skewed features (log transformation)
   - Handling class imbalance (SMOTE)
3. **Modeling**
   - Logistic Regression
   - Random Forest
   - XGBoost
4. **Evaluation**
   - ROC-AUC, precision, recall, F1-score
   - Confusion matrices
   - Comparison of models

## Results
- The best model achieved **ROC-AUC: 0.70**  
- Logistic Regression performed well after handling imbalance and preprocessing.  

## Conclusion
- This model can be used for **risk prioritization** in insurance.  
- Future improvements: hyperparameter tuning, feature engineering, more advanced ensemble methods.

## Author
Oluwakoya Adedayo
