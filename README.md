# Email Spam Detection Using Machine Learning
## Project Overview
This project implements various machine learning algorithms to classify emails as either spam or not spam using the "emails.csv" dataset. The dataset is processed, and algorithms such as Naive Bayes, K-Nearest Neighbors, and Decision Tree Classifier are used for classification. The code preprocesses the data, splits it into training and test sets, vectorizes the text, and evaluates the performance of the models based on accuracy scores and confusion matrices.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Description](#dataset-description)
3. [Installation and Setup](#installation-and-setup)
4. [ML Algorithms](#model-implementation)
5. [Evaluation Metrics](#evaluation-metrics)
   - Accuracy Score
   - Confusion Matrix
6. [Feedback](#feedback)
7. [Contributing](#contributing)

## Introduction :
With the vast increase in digital communication, particularly email usage, spam has become a significant issue. Spam emails, often containing unsolicited advertisements or harmful content, have led to increased demand for automated systems capable of filtering and classifying such messages accurately.
The primary objective of this project is to develop a machine learning-based spam classification model that can accurately predict whether an email is spam or not.
The project involves:
- Preprocessing the email text data.
- Applying multiple machine learning algorithms for classification.
- Comparing the performance of these models using evaluation metrics.
## Dataset Description :
The dataset used in this project (`emails.csv`) contains two columns:
- `text`: The content of the emails.
- `spam`: The label indicating whether the email is spam (`1`) or not (`0`).
### Data Overview :
- **Total Records**: 5728 emails
- **Number of Spam Emails**: 1368
- **Number of Non-Spam Emails**: 4360
## Installation and Setup :
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/spam-detection.git
   cd spam-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook spam_detection.ipynb
   ```
## ML Algorithms :
### 1. Naive Bayes (MultinomialNB): ####This is a probabilistic classifier that assumes the presence of features is independent of the others.It is well-suited for text classification problems such as spam detection.

### 2. K-Nearest Neighbors (KNN) : #### It assigns labels based on the nearest neighbors to the input data points.

### 3. Decision Tree Classifier : #### This method recursively splits the data into different branches based on feature values and applies classification at the leaves.

## Evaluation Metrics :
### 1. Accuracy Score
   - The `accuracy_score()` method is used to compute the accuracy of the predictions. It is calculated by dividing the number of correct predictions by the total number of predictions.
### 2. Confusion Matrix
   - The `confusion_matrix()` method provides insight into the number of true positives, false positives, true negatives, and false negatives.






## Contributing



## License

T


