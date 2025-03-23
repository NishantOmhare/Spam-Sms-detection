SMS Spam Detection

Introduction

This project is an SMS Spam Detection model that classifies text messages as either spam or ham (not spam). It leverages machine learning techniques to analyze and predict the nature of messages based on various text features.

Working

Data Collection: The dataset consists of labeled SMS messages, indicating whether they are spam or ham.

Data Preprocessing:

Removing special characters and punctuation

Converting text to lowercase

Tokenization and stopword removal

Applying TF-IDF vectorization

Model Selection and Training:

Various machine learning models are tested (e.g., Naive Bayes, SVM, Random Forest, etc.).

The best-performing model is selected based on evaluation metrics.
Usage

To run this project:

Install dependencies using:

pip install -r requirements.txt

Run the notebook or script to train and evaluate the model.

Use the trained model to classify new SMS messages.

Conclusion

This SMS Spam Detection model effectively distinguishes spam messages from ham messages with high accuracy. Future improvements may include deep learning models or real-time detection capabilities.


Evaluation:

The trained model is tested using precision, recall, and F1-score.

Confusion matrix analysis is performed to validate performance.

Deployment:

The model is integrated into a user interface or API for real-world usage.

Precision Output

Below are key performance metrics from the model evaluation:
Accuracy 0.9796905222437138
Precision 0.9834710743801653
