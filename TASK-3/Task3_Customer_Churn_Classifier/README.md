Predictive Customer Churn Classifier

Datheon Task 3 | Machine Learning | Random Forest & XGBoost

1. Project Overview

Customer churn prediction is a Machine Learning project that identifies customers who are likely to discontinue a telecommunications service. This project uses customer subscription records to train and evaluate classification models.

The project compares Random Forest and XGBoost classifiers and evaluates their performance using ROC-AUC, precision, recall, F1-score, and a confusion matrix.

2. Project Objectives

- Predict whether a customer is likely to churn.
- Clean and preprocess telecommunications customer data.
- Handle missing values and categorical features.
- Address class imbalance using class weighting.
- Train Random Forest and XGBoost classifiers.
- Compare model performance using ROC-AUC.
- Visualize ROC curves and confusion matrices.
- Identify the top 10 important features.

3. Dataset

Dataset: Telco Customer Churn

Source: "IBM Telco Customer Churn Dataset" (https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

The dataset contains customer demographics, account information, subscribed services, billing details, and churn status.

Target variable: "Churn"

- "Yes" — Customer churned.
- "No" — Customer did not churn.

The "customerID" column is excluded from model training because it is an identifier.

4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Jupyter Notebook

5. Machine Learning Algorithms

Random Forest Classifier

An ensemble algorithm that combines multiple decision trees to classify customers.

XGBoost Classifier

A gradient-boosting algorithm that builds trees sequentially to improve classification performance.

Class Imbalance Handling

Class weighting is used to give additional importance to the minority churn class during training.

6. Project Workflow

1. Load the Telco Customer Churn dataset.
2. Explore columns and missing values.
3. Convert "TotalCharges" to numeric format.
4. Remove duplicate records and handle missing values.
5. Separate features and the target variable.
6. Split data into training and testing sets.
7. Impute missing values and scale numerical features.
8. Encode categorical features using OneHotEncoder.
9. Train Random Forest and XGBoost models.
10. Evaluate classification performance.
11. Plot ROC curves and confusion matrices.
12. Extract the top 10 important features.
13. Save the trained model and prediction results.

7. Evaluation Metrics

- Accuracy: Percentage of correct predictions.
- Precision: Proportion of predicted churn cases that are actual churn cases.
- Recall: Proportion of actual churn cases correctly identified.
- F1-score: Balance between precision and recall.
- ROC-AUC: Measures how well the model distinguishes between churn and non-churn customers.

Target: ROC-AUC greater than 0.80, as specified in the task requirements. Actual performance depends on the trained model and dataset.

8. Project Structure

Task3_Customer_Churn_Classifier/
│
├── Task3_Customer_Churn_Classifier.ipynb
├── README.md
├── requirements.txt
├── output.png
│
└── outputs/
    ├── model_comparison.csv
    ├── evaluation_results.png
    ├── feature_importance.csv
    ├── feature_importance.png
    ├── churn_predictions.csv
    └── best_churn_model.pkl

9. Installation and Execution

Step 1: Clone the repository

git clone YOUR_GITHUB_REPOSITORY_URL

Step 2: Navigate to the project folder

cd Task3_Customer_Churn_Classifier

Step 3: Install dependencies

python -m pip install -r requirements.txt

Step 4: Run the notebook

Open "Task3_Customer_Churn_Classifier.ipynb" in VS Code or Jupyter Notebook and execute all five code cells in order.

An active internet connection is required to download the dataset.

10. Outputs

The project generates:

- Model performance comparison in CSV format.
- ROC curves for both classifiers.
- Confusion matrices.
- Classification reports.
- Top 10 feature importance visualization.
- Customer churn predictions and churn probabilities.
- Saved trained model in ".pkl" format.
- Final visualization saved as "output.png".

11. Conclusion

This project demonstrates an end-to-end customer churn prediction workflow using ensemble Machine Learning algorithms. It covers data preprocessing, class imbalance handling, model training, performance evaluation, and feature importance analysis.

The results can help demonstrate how Machine Learning can support customer retention analysis in telecommunications.

12. Author

Aleti Vignesh

B.Tech — Computer Science and Engineering, Artificial Intelligence and Machine Learning

Project: Predictive Customer Churn Classifier

Task: Datheon Task 3