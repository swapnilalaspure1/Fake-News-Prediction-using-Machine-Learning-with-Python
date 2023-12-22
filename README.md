# Fake-News-Prediction-using-Machine-Learning-with-Python

In this Fake News Prediction project, we performed the following steps:

Data Exploration and Preprocessing:
Loaded the training data from 'train.csv' and examined its structure.
Checked for duplicate rows and missing values, and handled them.
Merged the 'author' and 'title' columns into a new column named 'content'.
Applied stemming to normalize the text data.

Text Vectorization:
Used the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer to convert text data into numerical features.
Split the dataset into features (X) and labels (Y).

Random Forest Model Training:
Split the dataset into training and testing sets using the train_test_split function.
Trained a Random Forest model using Randomized Search Cross-Validation (RandomizedSearchCV) to find the best hyperparameters for the model.

Model Evaluation:
Evaluated the model's performance on both the training and testing datasets.
Calculated accuracy scores and generated a classification report, including precision, recall, and F1-score.
Visualized the confusion matrix to understand the model's predictions.

Making Predictions on New Data:
Created a predictive system to classify news as real or fake based on the trained model.
Imported test data from 'test.csv', preprocessed it, and applied the trained model to make predictions.
Saved the predictions along with corresponding IDs to a CSV file ('test_predictions.csv').

The project involved data cleaning, text preprocessing, feature engineering, model training, evaluation, and making predictions on new data. The Logistic Regression model was chosen and fine-tuned for this task, and the results were analyzed using various metrics to assess its performance.
