# credit-risk-classification

# Overview
The purpose of this analysis is to build a logistic regression model that predicts the credit risk (likelihood of default) of borrowers using historical data from a peer-to-peer lending services company. By analyzing borrower features and loan status, we aim to help the company make data-driven decisions when approving loans.

# Summary
The logistic regression model shows high overall accuracy, with particularly excellent performance for identifying healthy loans (Class 0). It also performs well in identifying high-risk loans (Class 1), though with slightly lower precision. This means while the model is very good at catching risky loans, it may still occasionally misclassify a healthy one as risky.

Given the balance of strong recall and reasonable precision for high-risk loans, this model is suitable for use in preliminary risk assessment. It can help minimize loan defaults by flagging potentially risky borrowers, although further validation or a more complex model might be needed for production deployment.

# Repository Structure

credit-risk-classification/

- credit_risk_classification.ipynb
- README.md
- report-template.md

Resources/

- lending_data.csv

# Technologies Used

- Python 3.9+

- pandas

- scikit-learn

- Jupyter Notebook

# Instructions to Run

- Clone this repository.

- Navigate to the Credit_Risk folder.

- Open credit_risk_classification.ipynb using Jupyter Notebook.

- Run the cells in order to execute the logistic regression model and generate performance metrics.

