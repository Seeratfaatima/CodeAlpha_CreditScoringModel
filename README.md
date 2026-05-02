# CodeAlpha: Credit Scoring Model

## 📌 Project Overview
This project was developed as part of the **Machine Learning Internship at CodeAlpha**. The objective is to predict an individual's creditworthiness using past financial data and classification algorithms.

## 🎯 Objective
To build a machine learning model that assesses the risk of a borrower based on historical financial indicators, allowing for better decision-making in loan approvals.

## 🛠️ Tech Stack & Tools
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
*   **Platform:** Kaggle / Jupyter Notebook

## 🚀 Machine Learning Workflow
1.  **Data Loading:** Utilized the **German Credit Risk** dataset.
2.  **Data Preprocessing:** 
    *   Handled missing values in financial columns.
    *   Encoded categorical variables (Sex, Housing, Checking/Saving account).
3.  **Feature Engineering:** Created a `Credit_per_Month` ratio to analyze the monthly repayment burden.
4.  **Data Splitting:** Performed an 80/20 train-test split before scaling to prevent **data leakage**.
5.  **Model Selection:** Implemented a **Random Forest Classifier**.
6.  **Scaling:** Used `StandardScaler` to normalize numerical features.

## 📊 Evaluation Results
According to the internship requirements, the model was evaluated using the following metrics[cite: 1]:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | ~75% |
| **ROC-AUC Score** | 0.78 |
| **Recall (Class 1)** | 0.89 |
| **F1-Score** | 0.83 |

### Confusion Matrix Insights
The model shows strong performance in identifying creditworthy individuals (high recall for "Good Risk"), which is essential for minimizing lost opportunities in lending.

## 📂 Repository Structure
*   `german_credit_data_analysis.ipynb`: Complete source code and analysis.
*   `german_credit_data.csv`: Dataset used for training and testing.
*   `README.md`: Project documentation.

## 🔗 Submission Details
*   **Task 1:** Credit Scoring Model.
*   **Internship Provider:** CodeAlpha.
