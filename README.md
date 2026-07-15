# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project uses a Random Forest Classifier to detect fraudulent credit card transactions. It demonstrates the complete machine learning workflow, from loading the dataset to saving and testing the trained model.

---

## Dataset

Source:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

- Total Transactions: 284,807
- Features: 30
- Target Variable: Class
  - 0 = Normal Transaction
  - 1 = Fraudulent Transaction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Train-Test Split
6. Model Training (Random Forest)
7. Prediction
8. Model Evaluation
9. Save Model
10. Load Model
11. Test Saved Model

---

## Results

Model: Random Forest Classifier

- Precision (Fraud): 0.81
- Recall (Fraud): 0.81
- F1-score (Fraud): 0.81
- Accuracy: Approximately 99.9%

---

## How to Run

```bash
git clone https://github.com/supratitsingh/Credit-Card-Fraud-Detection.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open:

```
Credit_Card_Fraud_Detection.ipynb
```

Run all notebook cells.

---

## Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- Streamlit web application
- Real-time fraud detection

---

## Author

**Supratit Singh**
<img width="890" height="588" alt="roc_curve" src="https://github.com/user-attachments/assets/b6a03f3a-44da-47cc-8a46-b8c62130035d" />
<img width="508" height="143" alt="confusion_matrix" src="https://github.com/user-attachments/assets/684aa484-755a-4dfe-b043-70863609e77e" />
<img width="894" height="394" alt="classification_report" src="https://github.com/user-attachments/assets/1ed1aedc-0067-40a2-9352-05aa1734ae0a" />
<img width="928" height="567" alt="class_distribution" src="https://github.com/user-attachments/assets/ccd5594f-1517-45da-bb6a-9d52ebbe0d96" />

