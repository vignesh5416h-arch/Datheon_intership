Real Estate Housing Price Prediction

1. Project Overview

The Real Estate Housing Price Prediction project uses Machine Learning algorithms to predict median house values based on housing and demographic features. The project uses the California Housing dataset and compares multiple regression models to identify the best-performing model.

2. Objectives

- Analyze housing data and identify important features.
- Clean and preprocess the dataset.
- Handle missing values and categorical variables.
- Train and compare Machine Learning regression models.
- Evaluate prediction performance using standard metrics.
- Visualize actual and predicted house prices.

3. Dataset

Dataset: California Housing Dataset

Source: "Housing CSV Dataset" (https://raw.githubusercontent.com/ageron/handson-ml2/master/datasets/housing/housing.csv)

The dataset contains information about California housing districts.

Target variable: "median_house_value"

Important features include:

- "longitude"
- "latitude"
- "housing_median_age"
- "total_rooms"
- "total_bedrooms"
- "population"
- "households"
- "median_income"
- "ocean_proximity"

4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

5. Machine Learning Algorithms

The following regression models are trained and compared:

1. Linear Regression
2. Ridge Regression
3. Random Forest Regressor

The best-performing model is selected based on the lowest Root Mean Squared Error (RMSE) on the test dataset.

6. Project Workflow

1. Load the housing dataset.
2. Explore the data and analyze missing values.
3. Remove duplicate rows.
4. Visualize house prices and feature correlations.
5. Separate input features and the target variable.
6. Split the data into training and testing sets.
7. Impute missing values and scale numerical features.
8. Encode categorical features.
9. Train three regression models.
10. Evaluate and compare model performance.
11. Generate house price predictions.
12. Save visualizations, results, and the trained model.

7. Evaluation Metrics

- MAE: Mean Absolute Error.
- RMSE: Root Mean Squared Error.
- R² Score: Measures how well the model explains variation in the target values.

The actual scores are generated when the notebook runs. Lower MAE and RMSE values generally indicate smaller prediction errors; a higher R² score generally indicates a better fit.

8. Project Structure

Task2_Housing_Price_Prediction/
│
├── Task2_Housing_Price_Prediction.ipynb
├── README.md
├── requirements.txt
├── output.png
│
└── outputs/
    ├── best_housing_model.pkl
    ├── model_comparison.csv
    ├── model_comparison.png
    ├── prediction_results.csv
    ├── house_price_distribution.png
    ├── house_prices_by_ocean.png
    ├── correlation_heatmap.png
    └── residual_distribution.png

9. Installation and Execution

Step 1: Clone the repository

git clone YOUR_GITHUB_REPOSITORY_URL

Step 2: Open the project folder

cd Task2_Housing_Price_Prediction

Step 3: Install dependencies

pip install -r requirements.txt

Step 4: Run the notebook

Open "Task2_Housing_Price_Prediction.ipynb" in Jupyter Notebook or VS Code and execute the cells in order.

An active internet connection is required to download the dataset from its source URL.

10. Results

The project generates:

- Model performance comparison.
- Actual versus predicted house price visualization.
- Sample house price prediction.
- Prediction error analysis.
- Saved trained Machine Learning model.
- Final visualization in "output.png".

11. Conclusion

This project demonstrates an end-to-end Machine Learning workflow for housing price prediction, including data analysis, preprocessing, model training, evaluation, and visualization. It provides practical experience with regression algorithms and model comparison.

12. Author

Aleti Vignesh

B.Tech — Computer Science and Engineering, Artificial Intelligence and Machine Learning

Project: Real Estate Housing Price Prediction