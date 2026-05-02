# CodeAlpha_CreditScoringModel
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
    *   Handled missing values in financial columns[cite: 1].
    *   Encoded categorical variables (Sex, Housing, Checking/Saving account)[cite: 1].
3.  **Feature Engineering:** Created a `Credit_per_Month` ratio to analyze the monthly repayment burden[cite: 1].
4.  **Data Splitting:** Performed an 80/20 train-test split before scaling to prevent **data leakage**.
5.  **Model Selection:** Implemented a **Random Forest Classifier**[cite: 1].
6.  **Scaling:** Used `StandardScaler` to normalize numerical features[cite: 1].

## 📊 Evaluation Results
According to the internship requirements, the model was evaluated using the following metrics[cite: 1]:

| Metric | Score |
| :--- | :--- |
| **Accuracy** | ~75% |
| **ROC-AUC Score** | 0.78 |
| **Recall (Class 1)** | 0.89 |
| **F1-Score** | 0.83 |

### Confusion Matrix Insights
The model shows strong performance in identifying creditworthy individuals (high recall for "Good Risk"), which is essential for minimizing lost opportunities in lending[cite: 1].

## 📂 Repository Structure
*   `Credit_Scoring_Model.ipynb`: Complete source code and analysis.
*   `german_credit_data.csv`: Dataset used for training and testing[cite: 1].
*   `README.md`: Project documentation.

## 🔗 Submission Details
*   **Task 1:** Credit Scoring Model[cite: 1].
*   **Internship Provider:** CodeAlpha[cite: 1].
