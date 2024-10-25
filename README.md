# Fake-News-Detection-Using-LSTM

Project Overview:
Fake news is a form of news consisting of deliberate disinformation or hoaxes spread via traditional news media or online social media.In this project, I have used different natural language processing (NLP) based machine learning and deep learning approaches including BERT to detect fake news from news headlines. Generally, a fake headline is a news headline which may read one way or state something as fact, but then the body of the article says something different. The Internet term for this type of misleading fake news is “clickbait” —headlines that catch a reader’s attention to make them click on the fake news. This type of fake news is misleading at best and untrue at worst.


In this project, I have extracted interesting patterns from the headline text using NLP and perform exploratory data analysis to provide useful insight about fake headlines by creating intuitive features. This project includes work detailed below:

1. Exploratory data analysis & Feature Engineering using NLP
2. Machine Learning Modeling using text based features
3. Deep Learning Modeling (LSTM) using text based features
4. BERT model building from tex based features


The dataset used in this project is the ISOT Fake News Dataset.The dataset contains two types of articles fake and real News. This dataset was collected from realworld sources; the truthful articles were obtained by crawling articles from Reuters.com (News website). As for the fake news articles, they were collected from different sources. The fake news articles were collected from unreliable websites that were flagged by Politifact (a fact-checking organization in the USA) and Wikipedia. The dataset contains different types of articles on different topics, however, the majority of articles focus on political and World news topics.

The dataset consists of two CSV files. The first file named True.csv contains more than 12,600 articles from reuter.com. The second file named Fake.csv contains more than 12,600 articles from different fake news outlet resources. Each article contains the following information:

1. article title (News Headline),
2. text,
3. type (REAL or FAKE)
4. the date the article was published on*
