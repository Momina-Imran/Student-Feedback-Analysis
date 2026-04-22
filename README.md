# Student-Feedback-Analysis
To develop and evaluate a machine learning model capable of classifying student feedback into sentiment categories (positive, negative, neutral) with high accuracy and reliability.
# Data Preprocessing
Text data underwent comprehensive cleaning and normalization:
•	Converted text to lowercase for consistency
•	Removed punctuation marks
•	Removed English stopwords to focus on meaningful content
•	Generated cleaned_text field for further processing
# Feature Extraction
TF-IDF (Term Frequency-Inverse Document Frequency) vectorization was applied with the following configuration:
•	N-gram range: (1, 2) - captures unigrams and bigrams
•	Maximum features: 3,000 - limits feature dimensionality
# Model Selection
Complement Naive Bayes was selected as the classification algorithm. ComplementNB is particularly effective for text classification tasks and handles imbalanced datasets well.
# Model Evaluation
The following evaluation strategy was implemented:
•	5-Fold Cross-Validation for robust performance estimation
•	80-20 train-test split for final model evaluation
•	Classification report with precision, recall, and F1-scores
# Two models were tested:
1.	Multinomial Naive Bayes 
2.	Complement Naive Bayes 
