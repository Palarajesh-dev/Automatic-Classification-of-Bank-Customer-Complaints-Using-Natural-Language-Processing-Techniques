# Automatic-Classification-of-Bank-Customer-Complaints-Using-Natural-Language-Processing-Techniques
Classification of bank customer complaints into predefined categories (e.g., credit reporting, debt collection, mortgages) using Natural Language Processing (NLP) techniques. It focuses on text preprocessing, exploratory data analysis, and preparing text data for machine learning models to improve efficiency in financial complaint management.
Project Overview
This repository contains a machine learning workflow designed to address the research question: How effectively can Natural Language Processing techniques be used to automatically classify bank customer complaints into predefined categories? By leveraging NLP, this project aims to categorize narratives provided by bank customers into specific financial product areas, enabling faster routing and resolution of issues.

# Dataset
The project utilizes a dataset of customer complaints (https://www.consumerfinance.gov/data-research/consumer-complaints/#get-the-data)containing:

narrative: The raw text of the customer's complaint.

product: The category or label associated with the complaint.

# Key Categories
Credit reporting

Debt collection

Mortgages and loans

Credit card

Retail banking

# Key Features
Data Preprocessing: Comprehensive text cleaning pipeline involving:

Removal of URLs, emails, and digits.

Tokenization and removal of special characters/punctuation.

Case normalization.

Handling of missing values and duplicate records.

# Exploratory Data Analysis (EDA):

Distribution analysis of complaint categories.

Word frequency analysis and Top 25 token identification.

Visualizations including bar charts, histograms for narrative lengths, and category-specific Word Clouds.

Data Preparation: Generation of a cleaned dataset (complaints_cleaned.csv) optimized for vectorization and modeling.

# Technologies Used
Python(colab)
Pandas: For data manipulation and cleaning.

Matplotlib: For data visualization.

WordCloud: For visual text analysis.

Regex (re): For advanced text cleaning operations.

How
