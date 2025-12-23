# Text-Intelligence-Sentiment-Analysis-of-IMDb-Reviews
IMDb Sentiment Analysis Report
Data Summary
•	Source: IMDb dataset with 50,000 reviews.
•	Columns: Two columns — review and sentiment.
•	Balance: Equal distribution of positive and negative reviews.
Preprocessing Steps
•	Removed HTML tags, URLs, and special characters.
•	Converted text to lowercase.
•	Tokenized and removed stopwords.
•	Applied stemming using PorterStemmer.
•	Dropped duplicate reviews.
•	Added word count feature.
•	Encoded sentiment: positive → 0, negative → 1.
Feature Extraction
•	Used TF-IDF Vectorizer to convert text into numerical features.
Modeling
Model	                        Accuracy	Precision	  Recall	  F1 score
Logistic Regression	            89.6	      89	       91      	91
Multinomial Naive Bayes	        86	        87	       86      	86
Linear SVC	                    89.9	      89         91      	91
				
•	Best Model: Linear SVC with C=1, loss='hinge' (selected via GridSearchCV).
•	Accuracy = 89.9%
Insights
•	Positive sentiment keywords: film, movie, great, story, time.
•	Negative sentiment keywords: bad, boring, slow, waste, disappointed.

VIDEO LINK: https://drive.google.com/file/d/1b2fa-dE9_cOeJp9bqi5QUKfPdyNYrS9h/view?usp=sharing

