# Email Spam Detection Using Machine Learning
This project implements various machine learning algorithms to classify emails as either spam or not spam using the "emails.csv" dataset. The dataset is processed, and algorithms such as Naive Bayes, K-Nearest Neighbors, and Decision Tree Classifier are used for classification. The code preprocesses the data, splits it into training and test sets, vectorizes the text, and evaluates the performance of the models based on accuracy scores and confusion matrices.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset ](#dataset)
3. [Installation ](#installation)
4. [ML Algorithms](#model-implementation)
5. [Evaluation Metrics](#evaluation-metrics)
6. [Results](#results)
7. [Contributing](#contributing)
8. [Feedback](#feedback)

## Introduction :
With the vast increase in digital communication, particularly email usage, spam has become a significant issue. Spam emails, often containing unsolicited advertisements or harmful content, have led to an increased demand for automated systems capable of accurately filtering and classifying such messages.
The primary objective of this project is to develop a machine learning-based spam classification model that can accurately predict whether an email is spam or not.

The project involves:
- Preprocessing the email text data.
- Applying multiple machine learning algorithms for classification.
- Comparing the performance of these models using evaluation metrics.
- Providing predictions and probabilities.
## Dataset :
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
### 1. Naive Bayes (MultinomialNB): 
This is a probabilistic classifier that assumes the presence of features is independent of the others.It is well-suited for text classification problems such as spam detection.

### 2. K-Nearest Neighbors (KNN) : 
This algorithm assigns labels based on the nearest neighbors to the input data points.

### 3. Decision Tree Classifier : 
This method recursively splits the data into different branches based on feature values and applies classification at the leaves.

## Evaluation Metrics :
### 1. Accuracy Score:
The `accuracy_score()` method computes the accuracy of the predictions, calculated by dividing the number of correct predictions by the total number of predictions.
### 2. Confusion Matrix:
The `confusion_matrix()` method provides insight into the number of true positives, false positives, true negatives, and false negatives.

## Results :
The performance of each algorithm is evaluated based on accuracy scores and confusion matrices. The results are printed at the end of the model training phase, allowing for a comparison of the effectiveness of each model in classifying spam emails.

## Contributing
Contributions are always welcome! Feel free to fork this repository, and submit a pull request to share your improvements with the community.

## Feedback
If you have any feedback or suggestions, please reach out via [email](#email).



