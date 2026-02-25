# Loan Status Prediction using Machine Learning

## Project Overview

This project aims to predict whether a loan application will be approved or rejected based on applicant details such as income, education, credit history, employment status, and property area.

The problem is a **binary classification task**, where the target variable is `Loan_Status`.

---

## Objective

To build a Machine Learning model that can accurately predict loan approval status using structured applicant data.

---

## Dataset Information

- Total Records: 614  
- Total Features: 13  
- Target Variable: `Loan_Status`  

### Important Features:
- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Credit_History  
- Property_Area  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Data Preprocessing

The following preprocessing steps were performed:

- Handled missing values using **Mode** (categorical) and **Median** (numerical)
- Encoded categorical variables into numerical format
- Split dataset into training and testing sets (80:20 ratio)

---

## Machine Learning Model

### Logistic Regression

Logistic Regression was used because:
- It is suitable for binary classification
- It is simple and efficient
- It performs well on structured tabular data

---

##  Model Performance

- **Accuracy:** 78.86%  
- Evaluation Metrics:
  - Confusion Matrix  
  - Precision  
  - Recall  
  - F1-Score  

The model performs well in predicting approved loans, with scope for improvement in predicting rejected loans.

---

## How to Run the Project

1. Clone the repository  
2. Install required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook  
4. Run all cells sequentially  

---

## Future Improvements

- Implement advanced models (Random Forest, SVM)
- Perform hyperparameter tuning
- Deploy as a web application
- Use larger real-world datasets

---

## Repository Structure

```
Loan-Status-Prediction-ML/
│
├── Loan_Status_Prediction.ipynb
├── loan.csv
├── Loan_Status_Prediction_Report_Shaurya_Gundre.pdf
├── Loan_Status_Prediction_Presentation_Shaurya_Gundre.pptx
├── requirements.txt
└── README.md
```

---

## Conclusion

This project demonstrates how Machine Learning can assist financial institutions in automating loan approval decisions efficiently and accurately.

