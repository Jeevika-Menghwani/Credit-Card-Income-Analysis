# 📊 Credit Card Data Analysis

📌 Project Overview

This project analyzes credit card usage data using data mining and statistical modeling techniques to identify key factors influencing income levels. It applies correlation analysis, linear regression, and multiple regression modeling to predict income based on financial and demographic variables.

📂 Dataset

📂 Dataset

📋 Name: CreditCard

🔢 Observations: 1,319

📊 Variables: 12

🔢 Numerical: Age, Income, Share, Expenditure, Dependents, Months, Active

📌 Discrete: Reports, Major Cards

📁 Categorical: Card Ownership, Self-Employment, Home Ownership

🔄 Project Workflow

1️⃣ Data Preprocessing
✔ Load and explore the dataset 📥

✔ Split into Training (60%) & Validation (40%) 📊

✔ Remove highly correlated features (e.g., share) to prevent multicollinearity ❌

2️⃣ Exploratory Data Analysis (EDA)
✔ Visualize relationships using scatter plots & regression lines 📈

✔ Compute correlation coefficients (e.g., Income vs. Dependents = 0.318) 🔍

✔ Perform hypothesis testing for statistical significance 🧠

3️⃣ Regression Modeling
✔ Simple Linear Regression (SLR): Income ~ Dependents 📊

✔ Multiple Linear Regression (MLR): Income ~ Age + Expenditure + Reports + Major Cards + Self-Employment + Home Ownership 🔢

✔ Backward Stepwise Regression: Optimize feature selection using AIC criteria 🎯

4️⃣ Model Evaluation & Prediction
✔ Calculate RMSE & MAE for training and validation sets 📊

✔ Compare model performances to detect overfitting 🔍

✔ Predict income for new individuals based on key factors 🎯

📊 Key Findings

👨‍👩‍👧‍👦 Dependents have a moderate positive correlation with income (0.318).

💰 Expenditure, home ownership, and self-employment significantly impact income.

📉 MLR outperforms SLR, but improvements are minor, indicating possible overfitting.

The model provides reasonable generalization on validation data, though additional socioeconomic factors could improve accuracy.

🛠 Technologies Used

🖥 R Programming (caret, ggplot2, forecast, AER)

📊 Data Visualization (scatter plots, regression plots)

📈 Statistical Analysis (correlation, regression modeling)

