# News-article-classification
This project performs classification of 2121 BBC news articles into categories using Multinomial Naive Bayes and Logistic Regression. A comparison is also drawn. 

# Methods
- Stemmed Tokenization, Document Term Matrix, feature vector selection, chi-square feature selection were used before training and testing.
- Different combinations of training and testing splits (80-20, 75-25, 70-30)% were used to identify the best combination.
- Mutinomial Naive Bayes and Logistic Regression was used as classification techniques.
- Confusion Matrix, Precision and Recall socres were calculated for comparison between the two methods.

# Tools
Python, Jupyter Notebook, pandas, numpy, nltk, sklearn

# Key results
- Overall 5000 features were retained after frequency based reduction and chi-square feature selection.
- Multinomial Naive Bayes outperformed Logistic Regression.
