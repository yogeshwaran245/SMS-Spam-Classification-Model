# SMS Spam Classification Model

This repository contains code for a machine learning model to classify SMS messages as spam or legitimate (ham). The model utilizes techniques like TF-IDF and classifiers including Logistic Regression and Multinomial Naive Bayes.

## Dataset

The dataset used for training the model can be found on [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset). This dataset contains two columns: `message` which represents the text of the SMS messages, and `label` which indicates whether the message is spam or ham.

## Libraries Used:

- pandas: Used for data manipulation and analysis.
- numpy: Used for numerical computations.
- scikit-learn: Utilized for building and evaluating machine learning models.
- warnings: Employed to ignore warning messages during code execution.

## Usage:

### Data Loading and Preprocessing:
The dataset is loaded using pandas, irrelevant columns are dropped, and the remaining columns are renamed for clarity. Duplicate entries are removed, and label encoding is applied to the target variable.

### Feature Engineering:
The text messages are transformed into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.

### Model Training and Evaluation:
The dataset is split into training and testing sets. Two classifiers, Logistic Regression and Multinomial Naive Bayes, are trained on the training data. The trained models are then evaluated using accuracy score on the testing data.

## Model Performance:

- Logistic Regression: Achieved an accuracy of X% on the testing set.
- Multinomial Naive Bayes: Achieved an accuracy of Y% on the testing set.

