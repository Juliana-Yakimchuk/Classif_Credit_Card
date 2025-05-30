# Credit Card Default Classification
This project analyzes and predicts whether a credit card client is likely to default on their payment next month based on various demographic and financial attributes.

## Dataset
Source: UCI Machine Learning Repository

Attributes: Demographic data (e.g., age, education, marriage), payment history, bill statement, and default status.

## Objective
To build and evaluate a machine learning model that classifies clients into defaulters and non-defaulters.

## Project Structure
bash
Copy
Edit
.
├── CC_Classification.ipynb              # Jupyter notebook with full analysis
├── requirements.txt                     # Python dependencies
└── README.md                            # Project documentation

## Methods
Logistic Regression for baseline modeling

StandardScaler for feature scaling

Classification metrics: Precision, Recall, F1-score, ROC-AUC

Visualizations: Confusion matrix, ROC curve

## Getting Started
Setup
Clone the repository or download the files.

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook Refactored_CC_Classification.ipynb
📈 Results
Baseline model: Logistic Regression

Evaluation includes confusion matrix, ROC curve, and classification report
## Future Work
Address class imbalance with resampling

Try ensemble models (Random Forest, XGBoost)

Use feature selection and advanced preprocessing

