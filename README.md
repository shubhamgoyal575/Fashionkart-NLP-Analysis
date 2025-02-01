## FashionKart Review Analysis & Recommendation Prediction 🚀
A comprehensive project that builds a text classifier to predict whether a customer will recommend a product based on their review, and uses topic modeling to extract and visualize the key themes emerging from customer reviews.

## 🔍 Overview
FashionKart connects consumers with the latest products from various e-commerce platforms. Customers share their experiences by leaving reviews, which serve as valuable feedback for other shoppers. This project aims to:
- Predict Product Recommendations: Build a text classifier that predicts whether a user will recommend a product in the future based on their review.
- Extract Key Topics: Apply topic modeling techniques to uncover the primary themes and topics within the reviews.
- Visualize Insights: Present the extracted topics through informative visualizations.

## 🎯 Project Objectives
- Text Classification: Use Natural Language Processing (NLP) techniques to build a classifier that distinguishes between reviews from users who would recommend a product and those who wouldn’t.
- Topic Modeling: Identify and visualize the key topics and themes that appear in customer reviews.
- Evaluation: Evaluate the classifier using accuracy metrics based on a held-out test set.

## 📁 Dataset
The project uses the dataset.csv file, which contains:
- Review: The text of the customer review.
- Recommendation: A binary indicator (e.g., 1 for recommend, 0 for not recommend) of whether the user recommends the product.

## 🛠️ Approach
#### Exploratory Data Analysis (EDA):
- Analyze review text length, word distributions, and recommendation balance.
- Visualize data distributions and insights.

#### Data Preprocessing:
- Clean the text data (remove punctuation, stop words, and perform tokenization).
- Convert text into numerical representations (e.g., TF-IDF, word embeddings).

#### Text Classification Modeling:
- Split data into training and test sets.
- Train multiple classification models (e.g., Logistic Regression, Support Vector Machines, etc.).
- Evaluate model performance using accuracy and AUC score.

#### Topic Modeling & Visualization:
- Apply algorithms such as Latent Dirichlet Allocation (LDA) to extract topics.
- Visualize topics using word clouds and other suitable plots.

## 💻 Tech Stack
- Programming Language: Python 🐍
- Libraries & Frameworks:
   - Data Handling: Pandas, NumPy
   - NLP: NLTK, spaCy, Gensim , pyLDAvis
   - Machine Learning: Scikit-Learn
   - Visualization: Matplotlib, Seaborn, WordCloud
   - Development: Jupyter Notebook
