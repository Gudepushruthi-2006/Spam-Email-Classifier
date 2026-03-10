# Spam Email Classifier

## Project Description

This project builds a machine learning model to classify messages as Spam or Ham (Not Spam). The model is trained using a dataset of SMS messages and uses text processing techniques to convert text into numerical features.

## Technologies Used

* Python
* Scikit-learn
* TF-IDF Vectorizer
* Naive Bayes Algorithm
* Google Colab

## How the Model Works

1. The dataset of SMS messages is loaded.
2. The messages are converted into numerical form using TF-IDF vectorization.
3. The dataset is split into training and testing data.
4. A Naive Bayes classifier is trained on the training data.
5. The model predicts whether a new message is Spam or Ham.

## Example

Input:
"You won a free lottery ticket"

Output:
Spam

## Dataset

The dataset used in this project is the **SMS Spam Collection Dataset**.

Location in repository: `dataset/sms.tsv`

Source: https://archive.ics.uci.edu/ml/datasets/sms+spam+collection
