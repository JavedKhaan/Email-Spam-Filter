# Email Classification Project

## Introduction

This project involves building a machine learning model to classify emails as either spam or not spam. The model is trained using a dataset of labeled emails, and various natural language processing (NLP) techniques are applied for feature extraction and preprocessing. The project utilizes the Naive Bayes algorithm, specifically the Multinomial Naive Bayes variant, Decision Tree Classification for classification.

## Dataset

The dataset used in this project contains labeled emails, where each email is tagged as either "ham" (not spam) or "spam." The dataset is assumed to be preprocessed and cleaned.

## Data Preprocessing

### Text Preprocessing

- The email text undergoes several preprocessing steps:
  - Conversion to lowercase
  - Tokenization using NLTK
  - Removal of non-alphanumeric characters and stopwords
  - Stemming using the Porter Stemmer

## Exploratory Data Analysis (EDA)

- EDA is performed to gain insights into the dataset's characteristics.
- Visualizations include pie charts of email categories (spam vs. not spam) and histograms of various text-related features.

## Model Training

- The Multinomial Naive Bayes algorithm is chosen for classification.
- Features are scaled using Min-Max scaling.
- The model is trained on the preprocessed and scaled data.

## Evaluation

- Model performance is evaluated using accuracy, precision, confusion matrix, and other relevant metrics.
- Separate evaluations are conducted for each category (spam and not spam).
- Visualizations, such as histograms, are used to analyze feature distributions.

## Usage

- A function is defined to classify new emails or sentences using the trained model.
- The user is prompted to input an email or sentence, and the model classifies it as spam or not spam.
- The input undergoes the same preprocessing steps as the training data before classification.

## Conclusion

This email classification project demonstrates the application of NLP techniques and the Multinomial Naive Bayes algorithm for binary classification. The project covers aspects of data preprocessing, exploratory data analysis, model training, evaluation, and practical usage.


