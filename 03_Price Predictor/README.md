🏡 House Price Prediction using Linear Regression

📌 Project Overview

This project demonstrates a complete machine learning workflow for predicting house prices using Linear Regression. It covers data preprocessing, model training, evaluation, and visualization, providing a clear example of how regression models can be applied to real‑world datasets.

⚙️ Workflow Steps

1. Import Libraries – pandas, numpy, scikit‑learn for preprocessing, modeling, and evaluation.

2. Load Dataset – HousePricePrediction.csv uploaded and explored.

3. Data Exploration – Dataset info, missing values check.

4. Handle Categorical Data – Converted categorical features into numeric values using LabelEncoder.

5. Handle Missing Values – Filled missing entries with column means.

6. Define Features & Target – Independent variables (X) vs dependent variable (SalePrice).

7. Train-Test Split – 80% training, 20% testing, reproducible with random_state=42.

8. Model Training – Linear Regression model fitted on training data.

9. Make Predictions – Predicted house prices on test set.

10. Model Evaluation – Metrics: MAE, MSE, RMSE, R² Score.

11. Interpretation – Insights into performance and improvement strategies.

12. Visualization – Scatter plots comparing actual vs predicted prices.

📊 Results

- Mean Absolute Error (MAE): ~32,448

- Root Mean Squared Error (RMSE): ~48,722

- R² Score: ~0.33

➡️ The model explains a portion of the variance in house prices but leaves room for improvement. Suggested enhancements include feature engineering, outlier removal, and advanced algorithms like Random Forest or XGBoost.

📸 Workflow Screenshots

The following images document the Linear Regression Workflow for the Price Predictor project.

You can view them directly in the repository:

👉 Screenshots Folder

🔑 Steps with Visuals

Train-Test Split  
https://github.com/Azizulhaq-professional/Aziz-Tech-Portfolio/blob/main/03_Price%20Predictor/screenshots/1_Train_Test.JPG

Linear Regression Model  
https://github.com/Azizulhaq-professional/Aziz-Tech-Portfolio/blob/main/03_Price%20Predictor/screenshots/2_Linear_Regression.JPG

Make Predictions  
https://github.com/Azizulhaq-professional/Aziz-Tech-Portfolio/blob/main/03_Price%20Predictor/screenshots/3_Make_Prediction.JPG

Evaluate Model  
https://github.com/Azizulhaq-professional/Aziz-Tech-Portfolio/blob/main/03_Price%20Predictor/screenshots/4_Evaluate_Model.JPG

Compare Actual vs Predicted  
https://github.com/Azizulhaq-professional/Aziz-Tech-Portfolio/blob/main/03_Price%20Predictor/screenshots/5_Compare.JPG

Graph Visualization  
https://github.com/Azizulhaq-professional/Aziz-Tech-Portfolio/blob/main/03_Price%20Predictor/screenshots/6_Graph.JPG

Perfect Fit Graph  
https://github.com/Azizulhaq-professional/Aziz-Tech-Portfolio/blob/main/03_Price%20Predictor/screenshots/7_Graph_Perfect_Fit.JPG

🛠️ Tech Stack

- Languages: Python

- Libraries: pandas, numpy, scikit‑learn, matplotlib

- Environment: Google Colab

🚀 Future Improvements

- Feature scaling and normalization

- Hyperparameter tuning

- Ensemble methods (Random Forest, XGBoost)

- Cross‑validation for robust evaluation

👤 Author

Developed by Aziz ul Haq
