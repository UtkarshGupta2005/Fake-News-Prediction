Problem Statement:
The rapid spread of fake news on digital platforms leads to misinformation, social unrest, and loss of trust. Automated detection systems are essential for content verification.

Objective:
To classify news articles as Fake or Real using Natural Language Processing and Deep Learning techniques.

Dataset:
News articles with labeled classes (fake / real)
Text-based dataset containing headlines and article content
Author name
Publishing Date
Title of the news
Source
Category : Politics, Technology, Healthcare, Business etc.

Methodology:
Text Preprocessing
Lowercasing
Removing punctuation and stopwords
lemmatization
Feature Engineering : Word2Vec embeddings

Model Training:
Long-Short Term Memory Unit Networks (LSTMs) 
Bidirectional LSTM
Gated Recurrent Unit Networks (GRUs)

Hyperparameter Tuning:
Evaluation Metrics
Accuracy
Callbacks: EarlyStopping
Using different Learning Rates with clipnorm=1.0

Results
LSTM model achieved 50.23% accuracy
GRU model achieved 50.25% accuracy

Tech Stack:
Python
NLTK
TensorFlow / Keras
Gensim
