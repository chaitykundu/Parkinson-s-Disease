# Detection of Parkinson's Disease using XGBoost

This repository implements a **Machine Learning pipeline** to detect Parkinson's Disease using patient data. The project leverages the **XGBoost algorithm** for classification and includes data preprocessing, model training, evaluation, and deployment guidance.

# 🔑 Key Features

## 1. Data Collection
- Uses the Parkinson's Voice dataset (`parkinsons.csv` or similar).  
- Contains features extracted from voice recordings or clinical measurements.  
- Dataset can be found in the `data/` directory.

## 2. Data Preprocessing
- Handles missing values.  
- Performs feature scaling and normalization.  
- Encodes categorical variables (if any).  

## 3. Model Training
- Trains an **XGBoost classifier** on the dataset.  
- Performs hyperparameter tuning to optimize performance.  
- Splits data into training and testing sets.  
- Saves the trained model under the `artifacts/` directory.

## 4. Model Evaluation
- Evaluates using metrics like:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
- Generates confusion matrix and classification reports.  

# 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/username/parkinsons-xgboost.git

