 # Automatic Classification of Bank Customer Complaints Using Natural Language Processing Techniques
 # Project Overview:

Banks receive thousands of customer complaints through various channels such as emails, websites, and customer support systems. Manually reviewing and categorising these complaints is time-consuming and inefficient.

This project uses Natural Language Processing (NLP) and Machine Learning techniques to automatically classify bank customer complaints into predefined categories. The system analyses textual complaint data and predicts the appropriate category, helping financial institutions improve complaint handling and response efficiency.

# Research Question:

How effectively can Natural Language Processing techniques be used to automatically classify bank customer complaints into predefined categories?

# Objectives:

To preprocess and clean textual complaint data.

To convert complaint text into numerical features using TF-IDF vectorisation.

To build machine learning models capable of classifying customer complaints.

To compare the performance of different machine learning algorithms.

To evaluate the effectiveness of NLP techniques for complaint classification.

# Dataset

The dataset used in this project contains bank customer complaints text and their corresponding categories.
Typical features in the dataset include:
Complaint description (text)
Complaint category
Other metadata related to customer complaints

# Dataset source example:

# CFPB Consumer Complaint Database
https://www.consumerfinance.gov/data-research/consumer-complaints/

# Project Workflow

The project follows a complete Natural Language Processing pipeline.
1. Data Collection
Customer complaint data is collected from publicly available complaint datasets.
2. Data Cleaning and Preprocessing
Text preprocessing steps include:
Converting text to lowercase
Removing punctuation and special characters
Removing stop words
Removing unnecessary whitespace
Handling missing values
3. Text Vectorisation
Text data cannot be directly used in machine learning models. Therefore, TF-IDF (Term Frequency–Inverse Document Frequency) is used to convert text into numerical features.
Vectorisation settings:
Unigrams and bigrams
Removal of common stop words
Feature dimensionality control
4. Machine Learning Models
Three machine learning models were implemented and compared.
Naive Bayes
A probabilistic classifier that performs well for text classification tasks.
Random Forest
An ensemble learning method that builds multiple decision trees and combines their predictions.
Linear Support Vector Machine (SVM)
A powerful classification algorithm widely used for high-dimensional text data.

# Model Evaluation

The models were evaluated using the following metrics:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
ROC Curve and AUC
These metrics help determine how well the models classify customer complaints into the correct categories.

# Exploratory Data Analysis

Exploratory analysis was performed to understand the dataset characteristics.
# Key analyses include:
Distribution of complaint categories
Text length analysis
Word frequency analysis
Category imbalance inspection
Results
The models were compared to determine which algorithm performs best for complaint classification.
# Key findings:

NLP techniques can effectively classify bank customer complaints.
Linear SVM generally performs strongly for high-dimensional text classification.
TF-IDF vectorisation provides meaningful numerical representations of complaint text.
Technologies Used
Python
Libraries used:
pandas
numpy
scikit-learn
matplotlib
seaborn
nltk
regex
Development Environment:
Jupyter Notebook
