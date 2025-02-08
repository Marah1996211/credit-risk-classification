# Credit Risk Classification

## Overview
In this project, we developed a machine learning model to predict loan risk using a dataset of historical lending activity from a peer-to-peer lending service. The goal is to assess the creditworthiness of borrowers and classify loans as either healthy (low risk) or high risk of defaulting. The project uses logistic regression to build the model and evaluate its performance.

## Analysis
The dataset contains information about loans, including features such as loan amount, term, interest rate, and borrower details. We split the data into training and testing sets and trained a logistic regression model to predict loan status. We evaluated the model's performance by generating a confusion matrix and printing the classification report, which includes metrics like accuracy, precision, recall, and F1-score.

## Results

- **Accuracy:** 99%
- **Precision (0 - Healthy Loan):** 1.00  
- **Recall (0 - Healthy Loan):** 1.00  
- **F1-score (0 - Healthy Loan):** 1.00  
- **Precision (1 - High-Risk Loan):** 0.87  
- **Recall (1 - High-Risk Loan):** 0.95  
- **F1-score (1 - High-Risk Loan):** 0.91  

## Summary
The logistic regression model performs exceptionally well in predicting both healthy and high-risk loans. It achieves perfect precision, recall, and F1-score for healthy loans, indicating flawless identification of low-risk loans. For high-risk loans, the model has strong recall (95%) but slightly lower precision (87%), suggesting it may occasionally misclassify some healthy loans as high-risk. However, the overall model performance is very strong, with an accuracy of 99%. Given these results, the model is highly recommended for use by the lending company to assess loan risk effectively.

## Files

- `credit_risk_classification.ipynb`: Jupyter notebook containing the code for data processing, model training, and evaluation.
- `lending_data.csv`: The dataset used for the project.
- `README.md`: This file with an overview and analysis of the project.

## Installation

1. Clone the repository:  
   `git clone https://github.com/<your-username>/credit-risk-classification.git`

2. Install required dependencies:  
   `pip install -r requirements.txt`

3. Run the notebook:  
   Open `credit_risk_classification.ipynb` in Jupyter Notebook and follow the steps to train the model and evaluate its performance.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.