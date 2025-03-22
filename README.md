# Fraud Detection Model

This project implements a machine learning model for detecting fraudulent transactions using Random Forest Classifier. The model is designed to handle highly imbalanced data and provides predictions for fraud detection.

## Features

- Random Forest Classifier with optimized parameters
- Handling of imbalanced data
- Feature engineering for transaction data
- Multiple encoding methods for categorical variables
- Threshold optimization for fraud detection

## Project Structure

- `improved_fraud_detection.py`: Main model implementation
- `improved_submission.csv`: Generated predictions
- `requirements.txt`: Package dependencies
- `transactions_train.csv`: Training dataset
- `transactions_test_wo_target.csv`: Test dataset
- `test_submission_template.csv`: Submission template

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the model:
```bash
python improved_fraud_detection.py
```

## Model Performance

- ROC-AUC Score: 0.8913
- Precision for fraud detection: 0.12
- Recall for fraud detection: 0.86
- F1-score for fraud detection: 0.20

## Data Distribution

- Training data: 0.0064% fraud cases
- Predictions: 0.0634% fraud cases (94 fraudulent transactions out of 148,228 total)
