# Sentiment Analysis on Restaurant Reviews

A Comprehensive NLP Pipeline Using Classical Machine Learning to Classify Review Sentiments

Project Description
This project focuses on sentiment analysis applied to a dataset containing 1,000 restaurant reviews, aiming to classify each review as expressing either a positive or negative sentiment. The analysis involves several key stages designed to transform raw text data into actionable insights through classical machine learning techniques.

The first phase involves extensive text preprocessing, where reviews are cleaned by removing punctuation and special characters, converting all text to lowercase for uniformity, and eliminating common stopwords—while deliberately retaining negation words like “not” to preserve sentiment context. Additionally, stemming is applied to reduce words to their root forms, helping to unify variations of the same word and improve feature consistency.

Following preprocessing, the cleaned text is transformed into numerical data using the Bag of Words model, implemented through CountVectorizer. This converts the textual information into a matrix of token counts, enabling machine learning algorithms to process the data effectively.

For model development, the project employs two widely-used classifiers: Naive Bayes and Decision Tree. Both models are trained on the vectorized data to learn patterns indicative of positive or negative sentiments in the reviews. The trained models are then evaluated on unseen test data to measure their predictive accuracy and robustness.

Model performance is assessed using standard classification metrics, including accuracy scores, confusion matrices that reveal true vs. predicted classifications, and comprehensive classification reports detailing precision, recall, and F1-scores. The Naive Bayes classifier achieved an accuracy of approximately 73% on the test set, demonstrating solid predictive capability given the dataset size and simplicity of features.

Overall, this project serves as a practical application of foundational natural language processing techniques combined with classical machine learning algorithms to analyze sentiment in real-world text data. It demonstrates the end-to-end workflow from raw data handling to model evaluation, suitable for anyone looking to understand or build sentiment analysis systems.
