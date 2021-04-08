# Twitter Sentiment Analysis - NLP

A “sentiment” is a generally binary opposition in opinions and expresses the feelings in the form of emotions, attitudes, opinions, and so on. It can express many opinions. For instance, “like,” or “dislike,” “good,” or “bad,” “for,” or “against,” along with others.

By using machine learning methods and natural language processing, we can extract the personal information of a document and attempt to classify it according to its polarity, such as positive, neutral, or negative, making sentiment analysis instrumental in determining the overall opinion of a defined objective, for instance, a selling item or predicting stock markets for a given company.

Nowadays, sentiment analysis is prevalent in many applications to analyze different circumstances, such as:

-> How Twitter users’ attitudes may have changed about the elected President since the US election?

-> Is this product review positive or negative?

-> Production companies can use public opinion to define the acceptance of their products and the public demand.

-> The prediction of election outcomes based on public opinion.

-> And many more!

# Dataset Information

In this project, we will import three datasets from NLTK that contain various tweets to train and test the model :~

1) negative_tweets.json: 5000 tweets with negative sentiments
2) positive_tweets.json: 5000 tweets with positive sentiments
3) tweets.20150430-223406.json: 20000 tweets with no sentiments

# Steps for building Twitter Sentiment Analysis Project :~

**Step 1) Installing NLTK and Downloading the Data**

**Step 2) Tokenizing the Data**

Language in its original form cannot be accurately processed by a machine, so you need to process the language to make it easier for the machine to understand.

Basically tokenization is splitting strings into smaller parts called tokens.

A basic way of breaking language into tokens is by splitting the text based on whitespace and punctuation.

**Step 3) Normalizing the Data**

Normalization in NLP is the process of converting a word to its canonical form.

Normalization helps group together words with the same meaning but different forms. Without normalization, “ran”, “runs”, and “running” would be treated as different words, even though you may want them to be treated as the same word. In this section, you explore stemming and lemmatization, which are two popular techniques of normalization.

1) Stemming is a process of removing affixes from a word. Stemming, working with only simple verb forms, is a heuristic process that removes the ends of words.

2) The lemmatization algorithm analyzes the structure of the word and its context to convert it to a normalized form.

**Step 4) Removing Noise from the Data**

In this step, you will remove noise from the dataset. Noise is any part of the text that does not add meaning or information to data.

Noise is specific to each project, so what constitutes noise in one project may not be in a different project. For instance, the most common words in a language are called stop words. Some examples of stop words are “is”, “the”, and “a”. They are generally irrelevant when processing language, unless a specific use case warrants their inclusion.

**Step 5) Determining Word Density**

**Step 6) Preparing Data for the Model**

          -> Converting Tokens to a Dictionary
          -> Splitting the Dataset for Training and Testing the Model
      
 **Step 7 — Building and Testing the Model**
 
Finally, you can use the "NaiveBayesClassifier" class to build the model. Use the ".train()" method to train the model and the ".accuracy()" method to test the model on the testing data.
          
To remove hyperlinks, you need to first search for a substring that matches a URL starting with http:// or https://, followed by letters, numbers, or special characters. Once a pattern is matched, the .sub() method replaces it with an empty string.

# Output
  ![Output](https://github.com/parthshingari28/Twitter-Sentiment-Analysis/blob/main/Output.png)
  
 Accuracy is defined as the percentage of tweets in the testing dataset for which the model was correctly able to predict the sentiment. A **99.7% accuracy** on the test set is pretty good.
 
 # Next, you can check how the model performs on random tweets from Twitter.
 
 **Example 1**
 ![example 1](https://github.com/parthshingari28/Twitter-Sentiment-Analysis/blob/main/Sample%20Tweets/example%201.png)
 
  **Example 2**
 ![example 2](https://github.com/parthshingari28/Twitter-Sentiment-Analysis/blob/main/Sample%20Tweets/example%202.png)
 
  **Example 3**
 ![example 3](https://github.com/parthshingari28/Twitter-Sentiment-Analysis/blob/main/Sample%20Tweets/example%203.png)
 
  **Example 4**
 ![example 4](https://github.com/parthshingari28/Twitter-Sentiment-Analysis/blob/main/Sample%20Tweets/example%204.png)
 
  **Example 5**
 ![example 5](https://github.com/parthshingari28/Twitter-Sentiment-Analysis/blob/main/Sample%20Tweets/example%205.png)
 
# Conclusion

Sentiment analysis aims at getting sentiment-related knowledge from data, especially now, due to the enormous amount of information on the internet. In other words, we can generally use a sentiment analysis approach to understand opinion in a set of documents.

Sentiment analysis is sometimes referred to as opinion mining, where we can use NLP, statistics, or machine learning methods to extract, identify, or otherwise characterize a text unit’s sentiment content.

Consumers can use sentiment analysis to research products and services before a purchase. Public companies can use public opinions to determine the acceptance of their products in high demand.

# Liked this Project ???

**Star it on [github](https://github.com/parthshingari28/Twitter-Sentiment-Analysis) !**

# Reach out at!

[@parthshingari28](https://github.com/parthshingari28)
