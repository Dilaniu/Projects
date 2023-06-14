# US-Economic-Sentiment-Analysisusing BERT
Topic Modeling and Sentiment Analysis on Reddit Comments
This repository contains code for performing topic modeling and sentiment analysis on Reddit comments. The project aims to analyze the sentiment expressed in Reddit comments and identify the main topics discussed.

Data Collection
The Reddit comments were collected using the PRAW API, which allowed us to access and retrieve comments from various subreddits. A total of 13 comments were collected for this analysis.

Topic Modeling
To perform topic modeling, we utilized the BERT topic model. This model utilizes BERT (Bidirectional Encoder Representations from Transformers) to identify the main topics present in the Reddit comments. By using BERT, we can capture the contextual information and semantic meaning of the comments more effectively.

Sentiment Analysis
For sentiment analysis, we employed the BERT model as well. To train our sentiment analysis model, we utilized a pre-trained stock dataset that already had sentiment labels (positive or negative). This allowed us to train the BERT model to classify sentiment based on the collected Reddit comments. The trained model was then used to make predictions on the sentiment (positive or negative) expressed in the comments.

Conclusion
By utilizing BERT for topic modeling and sentiment analysis, we were able to gain insights into the main topics discussed in the collected Reddit comments and understand the sentiment expressed in them. This analysis can be further extended and applied to other datasets or social media platforms to gain valuable insights.

References
BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding - Paper
PRAW: The Python Reddit API Wrapper - GitHub

