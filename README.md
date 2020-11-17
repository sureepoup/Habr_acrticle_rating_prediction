# Description
The task of this project was to research and develop a model for predicting the rating of articles on the habr.com resource using such features: date of publication of the article, the title of the article, the text of the article.

Applied various machine learning models to solve this problem. Made EDA, preprocessing, feature engineering, and anomaly detection.

Added features: weekday, year, month, hour, text_lenght. 

Applied machine learning models: Ridge Regression, Linear Regression, LightGBM.

Metric - MAE (Mean Absolute Error).

Best baselines:

Lemmas + TF-IDF Vectorizer + categorical variables + LightGBM.

Clean text + TF-IDF Vectorizer + categorical variables + LightGBM.

Technologies: numpy, prophet, matplotlib, scipy, sklearn, lightgbm, nltk, pymorphy2, altair, re.
