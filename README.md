# Upgrad_Data_Science_Hackathon
# Ecommerce Product Categorization

## Overview
This project focuses on automating the categorization of ecommerce products using natural language processing (NLP) and machine learning techniques. The dataset consists of product descriptions and categories obtained from an ecommerce platform. Key steps include data cleaning, exploratory data analysis, feature engineering, and model development for multi-class classification.

## Features
1. **Dataset Exploration**:
   - Initial dataset size: Train (14,999 entries), Test (2,534 entries).
   - Key columns: `description`, `product_category_tree`, `brand`.
   - High missing values in `brand` (4,710 in train, 522 in test).

2. **Data Cleaning**:
   - Removed duplicate and null entries.
   - Text normalization: lowercasing, punctuation removal, stopword filtering, and lemmatization.
   - Custom contractions handled, e.g., "women's" -> "women".

3. **Exploratory Data Analysis (EDA)**:
   - Bar charts for category distribution.
   - Text length analysis (max: 5309, min: 74, avg: 410).
   - Word clouds for frequent terms in descriptions.

4. **Feature Engineering**:
   - Converted text data to numerical features using Bag-of-Words and TF-IDF techniques.
   - Applied dimensionality reduction for efficient computation.

5. **Model Development**:
   - Trained multiple models: Logistic Regression, Random Forest, SVM, XGBoost, and Neural Networks.
   - Hyperparameter tuning for improved performance.
   - Compared models using accuracy and F1 scores.

6. **Results**:
   - Best performing model: SVM with 98.1% accuracy.
   - Model evaluation included accuracy scores, confusion matrices, and classification reports.

## Dependencies
- Python >= 3.7
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn, nltk, xgboost

## Key Visualizations
- Heatmaps for missing values.
- Bar plots for category distributions.
- Word clouds for frequent terms.
