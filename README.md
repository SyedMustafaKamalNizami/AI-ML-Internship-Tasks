# AI-ML-Internship-Tasks
Task 1 

Exploring and Visualizing a Simple Dataset

Objective:

To explore, analyze, and visualize the Iris dataset in order to understand its structure, relationships between features, and patterns that can be useful for classification tasks.

Dataset Used:

Iris dataset (150 samples, 4 features: sepal length, sepal width, petal length, petal width, and species).

Models Applied:

No machine learning model applied in this task — focused on data exploration and visualization.

Key Results & Findings:


1) Used pandas for data loading and exploration (.shape, .head(), .info(), .describe()).

2) Applied matplotlib and seaborn to create scatterplots, histograms, and boxplots.

3) Observed clear separation between species, especially in petal measurements.

4) Identified patterns that could be leveraged in classification models.


Task 2

Predicting House Prices using Regression

Objective:
To build a regression model that predicts median house prices based on housing features, applying feature engineering, feature scaling, and model evaluation techniques.

Dataset Used:

California Housing Dataset (includes features like total rooms, bedrooms, population, households, and proximity to ocean).

Models Applied:

Linear Regression (used to predict continuous house price values based on processed input features).

Key Results & Findings:

1) Cleaned dataset by removing missing values and log-transformed skewed features for normalization.

2) Used a correlation heatmap to explore relationships and guide feature engineering, including creation of the bedroom_ratio feature.

3) Applied one-hot encoding to handle categorical variables (ocean_proximity).

4) Performed feature scaling using StandardScaler, fitted only on training data to avoid data leakage.

5) Trained a linear regression model and evaluated it using MAE, RMSE, and R².

6) Achieved good model performance and visualized actual vs. predicted prices, confirming the model's ability to learn meaningful patterns.



