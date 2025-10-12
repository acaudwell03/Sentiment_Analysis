# Sentiment_Analysis
Final project for my MSc Data Science course. Includes a fine-grained sentiment analysis comparison between 3 models using the GoEmotions dataset by Google's Research Team.

This includes:
* CNN.ipynb: Data preprocessing, training, evaluation, and demonstration for CNN model
* CNN.py: CNN Architecture
* classes.py: Classes and functions for preprocessing, training, and evaluating models
* random_forest.ipynb: Data preprocessing, training, evaluation, and demonstration for random forest model
* roberta.ipynb: Data preprocessing, training, evaluation, and demonstration for RoBERTa model
* stats.r: Statistical analysis between models, including ANOVA and correlation analysis

Results demonstrated: 
* RoBERTa model performed better than the RF and CNN models, achieving an average F1-score of 71%
* RF model performed better with emotions with less samples (e.g. Grief, Pride)
* Weak positive correlation was found between sample size and performance
* SHAP Analysis shows how the RoBERTa model is able to use context to differentiate between similar emotions
