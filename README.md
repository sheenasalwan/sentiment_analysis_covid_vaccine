# Sentiment Analysis of Covid Vaccine data
Sentiment analysis of covid vaccine data collected from twitter

## Pipeline followed:
### Data Collection:
  - Setup developer account for TwitterAPI
  - Use python Tweepy to connect the API
  - Extract data related to Covid19 Vaccine
  - type of features
### Data Exploring
  - load data in data frame
  - check data types
  - check missing values
### Text Cleaning and Processing
  - convert text to lowercase
  - process text to remove url, punctuation, stopwords
  - lemmatization
  - convert emoji to text
### Feature Extraction
  - Average length of sentence
  - make pipeline
  - column tranformer
5. Baseline Model
    - Dummy Classifier
6. Linear Models
    - LogisticRegression, with class weights, SMOTE
    - pick one and perform Hyperparameter Optimization
7. Different Classifiers
    - Try different models
      - SVM
      - Tree based models:
        - Random Forest
        - XGBoost
        - LGBM
    - check for overfitting, underfitting
    - pick best models for further hyperparameter optimization
8. Feature Selection
    - Recursive feature elimination 
9. Hyperparamter Optimization
    - GridSearchCV/RamdomSearchCV
    - Check fit time, train and validation scores
    - pick the best estimator
10. Interpretation and feature importance
    - feature_importance_
    - eli5
    - SHAP
11. Results on test set
    - check results with best estimator
    - check consistency with validation scores
    - check for optimization bias
    - Interpret predictions - confusion matrix, classification report, SHAP
  