# AI-ML-Internship-Tasks
Task 1 

Exploring and Visualizing a Simple Dataset

Objective


To explore, analyze, and visualize the Iris dataset in order to understand its structure, relationships between features, and patterns that can be useful for classification tasks.

Dataset Used

Iris dataset (150 samples, 4 features: sepal length, sepal width, petal length, petal width, and species).

Models Applied

No machine learning model applied in this task — focused on data exploration and visualization.

Key Results & Findings


1) Used pandas for data loading and exploration (.shape, .head(), .info(), .describe()).

2) Applied matplotlib and seaborn to create scatterplots, histograms, and boxplots.

3) Observed clear separation between species, especially in petal measurements.

4) Identified patterns that could be leveraged in classification models.


Task 2

Predicting House Prices using Regression

Objective

To build a regression model that predicts median house prices based on housing features, applying feature engineering, feature scaling, and model evaluation techniques.

Dataset Used

California Housing Dataset (includes features like total rooms, bedrooms, population, households, proximity to ocean, coordinates etc).

Models Applied

Linear Regression (used to predict continuous house price values based on processed input features).

Key Results & Findings

1) Cleaned dataset by removing missing values and log-transformed skewed features for normalization.

2) Used a correlation heatmap to explore relationships and guide feature engineering, including creation of the bedroom_ratio feature.

3) Applied one-hot encoding to handle categorical variables (ocean_proximity).

4) Performed feature scaling using StandardScaler, fitted only on training data to avoid data leakage.

5) Trained a linear regression model and evaluated it using MAE, RMSE, and R².

6) visualized actual vs. predicted prices.


Task 3

General Health Query Chatbot (Prompt Engineering Based) 

Objective

To create an AI-powered chatbot capable of answering safe, friendly, and general health-related questions. The chatbot processes user queries, sends them to an AI model via an API, and returns clear, helpful responses within the health domain.

Dataset Used

No static dataset was used. Instead, the chatbot utilized real-time responses from the DeepSeek R1 model accessed through the OpenRouter API. This allowed the chatbot to handle natural language health queries dynamically without storing or processing large datasets locally.

Models Applied

DeepSeek R1 (accessed via OpenRouter API) – A large language model used for generating health-related responses based on user input.


Key Results & Findings


1) Successfully answered various health-related queries with clear and friendly responses.

2) Integrated Python’s requests library for sending HTTP POST requests to the API.

3) Used environment variables to securely store the API key, following security best practices.

4) Discovered that without content filtering, the chatbot could still answer unrelated topics (e.g., sports or celebrities), indicating a need for topic              restriction logic.

5) Leveraging the API eliminated the need for local model hosting or training, making the solution lightweight and easy to deploy.

