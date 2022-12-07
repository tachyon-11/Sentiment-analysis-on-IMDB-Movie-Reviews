# Sentiment-analysis-on-IMDB-Movie-Reviews
The aim of this project is to perform sentiment analysis on Movies reviews from IMDB. I have performed sentiment analysis using various models such as Support Vector Machines, Logistic Regression, Naïve Bayes and Recurrent Neural Network with LSTM (Long Short Term Memory)


# Files
I have used the following dataset available on Kaggle to train and test my models [Link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

# Procedure

 1. ### Performed Data Analysis and Pre-processing like :
      <ul>
      <li>Tokenization and stemming
      <li>   Removal of HTML strips and noise text (analyzed from Word Clouds and data analysis tools)
      <li> Remove Special Characters and stop words
      </ul>
 2. ### Vectorization of tweets
      <ul>
      <li>Bags of words model
      <li>Term Frequency-Inverse Document Frequency model (TFIDF)
      </ul>
     
 3. ### Machine Learning for Sentiment Analysis
      Applied and evaluated the results obtained by applying the following machine learning models using 'scikit0learn' library:
      | Machine Learning Model | BOW Model Accuracy (%) | TFIDF Model Accuracy (%)|
      |---------------------------------|-------------|-------------|
      | Logistic Regression | 75.12 | 75|
      |Naïve Bayes Classifier| 75.1 | 75.09|
      |Support Vector Machines| 58.29 | 51.12|
  
 4. ### Sentient analysis using Neural Network
     Long Short-Term Memory (LSTM) networks are a modified version of recurrent neural networks, which makes it easier to remember past data in memory.
     I encoded my tweets in form of vector in form input to the neural network and trained the model.
     I got an accuracy of 87.81 %

# Exploratory Data Analysis

I used Wordcloud to form the Word Cloud for positive as well as negative sentiment tweets to get a overview of most of the words used in those tweets

# Possible Improvements
<ul>
<li>Sometimes some sentences may have sarcasm or use of oxymorons which this model won't be able to understand
<li>This model doesn't put emphaisis on comparative and superlative degree of word and doesn't give them extra emphasis than normal words
<li>Currently this model is not taking into consideration any emoticons hence causing it to miss on important information regarding the review
</ul>

