# Boston House Price Prediction
This project uses the Boston Housing dataset to build a regression model that predicts the median value of homes based on various economic and geographic features.

Problem Statement:
To predict MEDV (Median value of owner-occupied homes) using features like crime rate, number of rooms, tax rate, and others, applying Linear Regression and visual analytics.

Dataset Overview
The dataset contains 506 rows and 14 columns:
| Feature   | Description                                 |
| --------- | ------------------------------------------- |
| `CRIM`    | Crime rate per capita                       |
| `ZN`      | Proportion of residential land zoned        |
| `INDUS`   | Industrial acres per town                   |
| `CHAS`    | Charles River dummy variable                |
| `NX`      | Nitric oxide concentration                  |
| `RM`      | Average rooms per dwelling                  |
| `AGE`     | % of owner-occupied homes built before 1940 |
| `DIS`     | Distance to employment centres              |
| `RAD`     | Accessibility to highways                   |
| `TAX`     | Property tax rate                           |
| `PTRATIO` | Student-teacher ratio                       |
| `B`       | % of Black population (formula-based)       |
| `LSTAT`   | % lower status of population                |
| `MEDV`    | Median house price (target)                 |


Workflow
1. Data Cleaning
      Checked for null values
      Capped outliers above MEDV > 45

2. Exploratory Data Analysis (EDA)
      Plotted distributions of MEDV, CRIM, LSTAT, etc.
      Correlation heatmap and pairplots

3. Model Building
      Used Linear Regression
      Explored performance based on different random_state values

4. Model Evaluation
      Metrics used: R², MAE, MSE, RMSE
      Best R² Score: 0.72



Tools & Technologies
1. Python (pandas, numpy, matplotlib, seaborn)
2. scikit-learn (LinearRegression, train_test_split, metrics)
3. Jupyter Notebook
