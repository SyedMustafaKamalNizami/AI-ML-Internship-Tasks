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

Task 4

News Title Classifier Using BERT

Objective

To fine-tune a transformer model (BERT) for classifying news headlines into predefined topic categories. The model learns to recognize patterns in text and categorize each headline into labels such as World, Sports, Business, and Sci/Tech.

Dataset Used

AG News Dataset (available on Hugging Face Datasets).

Contains 120,000 training samples and 7,600 test samples across four categories:

1) World

2) Sports

3) Business

4) Science & Technology

Methodology

1) Data Preprocessing

Loaded dataset using Hugging Face datasets library.

Tokenized text with BertTokenizer (bert-base-uncased).

Padded and truncated sequences to ensure uniform input length.

2) Model Fine-tuning

Used bert-base-uncased from Hugging Face Transformers.

Added classification head on top of BERT.

Fine-tuned using TrainingArguments with Adam optimizer and learning rate scheduling.

3) Evaluation

Evaluated performance using accuracy and F1-score.

Compared predictions with true labels on the test set.

4) Deployment

Integrated model with Gradio for a simple web-based interface.

Allowed users to input a news headline and instantly receive predicted category with confidence score.

Models Applied

BERT (bert-base-uncased)

Pre-trained on large text corpus.

Fine-tuned specifically for AG News classification.

Key Results & Findings

1) Achieved high accuracy and strong F1-scores across categories.

2) Model correctly classified unseen news headlines into World, Sports, Business, and Sci/Tech.

3) Deployment with Gradio provided real-time interaction with users.

4) Observed occasional misclassification for headlines with ambiguous context (e.g., business vs. world politics).

5) Demonstrated the effectiveness of transfer learning with BERT for text classification tasks.
