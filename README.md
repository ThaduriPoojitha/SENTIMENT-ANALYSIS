# SENTIMENT-ANALYSIS

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:Thaduri Poojitha

*INTERN ID*:CT04DF1335

*DOMAIN*:DATA ANALYTICS

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTHOSH

##YOU HAVE TO ENTER DESCRIPTION OF YOUR TASK Project Title: Sentiment Analysis Using Machine Learning

1. Introduction

Sentiment analysis, also known as opinion mining, is a subfield of Natural Language Processing (NLP) that aims to determine the emotional tone behind pieces of text. It is widely used in areas such as customer feedback analysis, product reviews, and social media monitoring. The primary objective of this project is to build a sentiment classification model that categorizes textual data into predefined sentiments like positive, negative, or neutral.

In this project, we develop a machine learning-based sentiment analysis system using a logistic regression classifier. We perform text preprocessing, feature extraction, model training, and evaluation to predict the sentiment of user-provided statements. This project demonstrates a complete workflow of a real-world NLP application.
2. Problem Statement

With the explosive growth of user-generated content on platforms like Twitter, YouTube, and e-commerce websites, it becomes crucial for organizations to automatically analyze public opinion. Manually analyzing thousands of reviews or social posts is not feasible. This is where sentiment analysis comes into play. The challenge is to accurately classify free-form text, which may include slang, sarcasm, or grammatical errors, into relevant sentiment categories.
3. Methodology

3.1 Dataset Preparation

In our approach, we created a sample dataset consisting of user feedback labeled with sentiments: positive, negative, and neutral. The dataset includes short textual reviews or opinions to simulate real-world usage.

3.2 Text Preprocessing

Text preprocessing is essential in NLP to convert raw text into a structured form suitable for machine learning algorithms. The following steps were performed:

Lowercasing all text

Removing special characters, punctuation, and numbers

Eliminating stopwords (commonly used words such as "the", "is", "and" which do not contribute much to sentiment)

Tokenizing and vectorizing the cleaned text

3.3 Feature Extraction

We used the Bag-of-Words model through CountVectorizer to convert the cleaned text into numerical vectors. This model counts the frequency of each word and represents text data as a sparse matrix suitable for machine learning input.

3.4 Model Training and Evaluation

We employed Logistic Regression, a widely used and efficient classification algorithm. The model was trained using 70% of the dataset and tested on the remaining 30%. The performance of the model was evaluated using a confusion matrix and classification report, including metrics like precision, recall, and F1-score.
4. Results

The model achieved high accuracy on the test dataset, effectively distinguishing between positive, negative, and neutral sentiments. The confusion matrix revealed low misclassification rates. Additionally, the model successfully predicted the sentiments of new unseen user inputs such as:

“I absolutely loved the experience.” → Positive

“This was the worst ever.” → Negative

“Just okay, not bad.” → Neutral

This demonstrates the practical usability of the model in real-time scenarios.
5. Conclusion

This project showcases the successful implementation of a sentiment analysis system using basic NLP and machine learning techniques. Despite using a simple model and limited data, the results were promising and aligned with expected outputs. In real-world applications, such systems can be scaled with larger datasets and deep learning techniques like LSTM or BERT for even better performance.


#OUTPUT

<img width="534" alt="Image" src="https://github.com/user-attachments/assets/7a18b643-70f1-48a9-9e46-37238a9fa2c5" />
