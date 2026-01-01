# PEP-NLP-CricketSentiment 

**PEP Project 3: Live Cricket Match Sentiment Analysis**

##  Problem Statement
Classify fan tweets/reviews as **Positive/Negative/Neutral** during live IPL/World Cup matches

## Dataset
- **Source**: Football Sentiment Analysis (Kaggle) [adapted for cricket]
- **Size**: 10K+ labeled tweets
- **Labels**: Positive (60%), Negative (20%), Neutral (20%)

##  Tech Stack
Python | scikit-learn | NLTK | TF-IDF | Logistic Regression
pandas | matplotlib | seaborn | wordcloud

text
##  Results
- **Accuracy**: 88.5%
- **F1-Score**: 0.87 (weighted avg)

##  Quick Demo
predict_sentiment("India chased 200 in 18 overs! Rohit fireworks 🔥")

Output: POSITIVE (95% confidence)