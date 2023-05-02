# CMP262-Project4
## Sentiment Analysis of Yelp Reviews

In this project, students were asked to use the Yelp Fusion API to download review data and perform sentiment analysis. Sentiment analysis was performed via the TextBlob library and utilized the default analyzer as well as the NaiveBayesAnalyzer.  Positive, negative, and neutral sentiments were tallied from both analyses, and donut charts were produced.  

Following this, the review data was cleaned to create a WordCloud of the Top 20 words that appeared in the downloaded reviews. The list of words from the review was compared against the NLTK Stop Word list, and all stop words were removed.  The resulting list was used to create the WordCloud.