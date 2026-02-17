# SENTIMENT-ANALYSIS-WITH-NLP

COMPANY: CODTECH IT SOLUTIONS

NAME : SMRUTI NILESH DHARU

INTERN ID::CTIS4838

DOMAIN: MACHINE INTELLIGENCE

DURATION: 4 WEEKS

MENTOR:NEELA SANTHOSH

#DESCRIPTION OF THE TASK:Sentiment Analysis of Uber Customer Reviews Using Machine Learning
##PROJECT OVERVIEW:

This project focuses on performing sentiment analysis on Uber customer reviews using Natural Language Processing (NLP) and machine learning techniques. The objective is to automatically classify customer feedback as positive or negative based on the textual content of reviews. Understanding customer sentiment is crucial for service-based platforms like Uber, as it helps in identifying customer satisfaction levels, service issues, and areas for improvement.

##TOOLS AND TECHNOLOGIES USED:
🔹 Programming Language

Python 3.11

Chosen for its extensive support for data analysis, NLP, and machine learning libraries.

🔹 Development Environment / Editor

Visual Studio Code (VS Code)

Used as the primary editor and development platform.

Extensions used:

Python (Microsoft) – for Python development and debugging.

Jupyter (Microsoft) – to create and run Jupyter Notebook files (.ipynb) directly inside VS Code.

🔹 Libraries & Frameworks

The following Python libraries were used throughout the project:

Pandas – for data loading, cleaning, and manipulation.

NumPy – for numerical operations and array handling.

NLTK (Natural Language Toolkit) – for text preprocessing, stopword removal, and basic NLP utilities.

Scikit-learn – for machine learning tasks such as:

Train-test splitting

TF-IDF vectorization

Logistic Regression modeling

Model evaluation metrics

Matplotlib & Seaborn – for data visualization and graphical analysis of results.

##DATASET DESCRIPTION:

The dataset consists of Uber customer reviews downloaded in CSV format. It contains multiple columns, including:

content – textual customer review

score – user rating (1 to 5)

Additional metadata such as username, app version, and review timestamps

For the purpose of sentiment analysis, only the content and score columns were used. Ratings were converted into sentiment labels as follows:

Positive (1): Ratings ≥ 4

Negative (0): Ratings ≤ 2

Neutral (3): Removed to maintain clear binary classification

##PROJECT WORKFLOW:
1.Data Loading and cleaning
2.Text Preprocessing
3.Feature Extraction (TF-IDF)
4.Model Training
5.Model Evaluation
6.Visualization & Analysis

##OUTPUT:
