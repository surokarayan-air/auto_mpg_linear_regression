🚗 auto_mpg_linear_regression

This repository implements a multiple linear regression model to predict automobile fuel efficiency (miles per gallon) using the Auto MPG dataset.

📌 Project Overview

The goal of this project is to analyze how different car characteristics affect fuel consumption and to build a linear regression model for predicting miles per gallon (mpg).

The project includes:
- Loading and preprocessing the Auto MPG dataset
- Feature scaling using StandardScaler
- Training a multiple linear regression model
- Evaluating model performance using RMSE and R² metrics

📊 Dataset

The Auto MPG dataset contains fuel economy data and technical specifications for automobiles.

Features used in this project:
- mpg — Miles per gallon (target variable)
- cylinders
- displacement
- horsepower
- weight
- acceleration
- model year
- origin

The dataset file `mpg.csv` included in this repository is used for both training and testing.

⚙️ Methodology

1. Feature and target separation  
2. Train / test split  
3. Feature scaling with StandardScaler  
4. Multiple linear regression training  
5. Model evaluation using RMSE and R²  

📈 Results

The model demonstrates how automobile features such as weight, horsepower, and engine size influence fuel efficiency.  
Evaluation metrics provide insight into prediction accuracy and overall model performance.

🛠 Libraries Used

- numpy
- pandas
- scikit-learn

🧠 Notes

This project is for educational purposes and can be extended with:
- Feature engineering
- Polynomial regression
- Regularization methods (Ridge, Lasso)
- Other regression models
