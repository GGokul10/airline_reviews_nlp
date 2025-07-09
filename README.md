Airline Reviews Rating Prediction Using NLP
Project Overview
This project focuses on analyzing airline customer reviews using Natural Language Processing (NLP) techniques to predict overall satisfaction ratings. It leverages a dataset of over 8,000 reviews containing both textual feedback and structured service ratings.

Key Features
Text Preprocessing: Cleaning and normalization of review texts, including lowercasing, punctuation removal, and stopword filtering to prepare data for modeling.

Feature Engineering: Conversion of processed text into numerical features using TF-IDF vectorization with unigrams and bigrams to capture important word patterns.

Modeling: Training of a regression model (Linear Regression or Random Forest) to predict overall customer ratings based on review text features.

Evaluation: Model performance assessed using Mean Squared Error (MSE), achieving a value of approximately 25.71 on the test set, indicating the average squared prediction error.

Insights: The project demonstrates the potential and challenges of predicting customer satisfaction from unstructured text, laying groundwork for further improvements with advanced NLP and modeling techniques.

Usage
The code includes data loading, preprocessing, feature extraction, model training, prediction, and evaluation steps. Visualization of predicted versus actual ratings helps in understanding model effectiveness.
