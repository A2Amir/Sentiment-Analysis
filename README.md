## 1. Introduction

Sentiment Analysis is probably one of the most popular uses of natural language processing these days. Sentiment Analysis has become an important tool for many purposes. **For example:** 
<b>
 
 * understanding customer sentiment around the company for making investment decisions, 
 
 * getting a feedback signal for social media and advertising campaigns, 
 
 * as a quantitative measure for book and movie reviews.
 </b>
 
## 2. Sentiment Analysis with Naive Bayes, Gradient Boosting Classifier and LSTM (Tensorflow 2)

The notebooks below will train two macchine learning and LSTM deep leaning classifiers by using  movie reviews in the Internet Movie Database or IMDB dataset. The dataset I am going to use is very popular among researchers in Natural Language Processing, usually referred to as [the IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/). It consists of movie reviews from the website imdb.com, each labeled as either 'positive', if the reviewer enjoyed the film, or 'negative' otherwise.
 
* [The first notebook](https://github.com/A2Amir/Sentiment-Analysis/blob/master/sentiment_analysis.ipynb) will do it with two regular supervised learning classifiers(Naive Bayes, Gradient Boosting Classifier) by  looking at a review as an unorganized collection of words. to use this notebook, first download [the IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/) then extrac it to the folder named data/imdb-reviews
 
* [The second notebook](https://github.com/A2Amir/Sentiment-Analysis/blob/master/lstm_sentiment_analysis.ipynb) will exploit the sequentiality of the sentences and will train a more accurate classifier using a recurring neural network. 



##### to use 
## 3. Sentiment Analysis with logistic Regression and Fully Connected layer and LSTM (Tensorflow 1)


In this  [notebook](https://github.com/A2Amir/Sentiment-Analysis/blob/master/Sentiment%20Analysis.ipynb), I am going to looking at how to apply Logistic Regression to the task of sentiment analysis. Sentiment analysis can be thought of as the exercise of taking a sentence, paragraph, document, or any piece of natural language, and determining whether that text is emotional tone is positive or negative. 

#### Data Preprocessing
Some steps are necessary to prepare our dataset

        1- Tokenizing, it is when you convert words into numbers-->[“The”, “cat”, “went”, “to”, “the”, “zoo”, “.”] it would be              tokenized to [1, 2, 3, 4, 1, 5, 6]. it  is done by Keeras

        2- The next step is to make all of the reviews the same length.------> max_review_length = 70

        3- Convert all labels into One Hot Encoding 

        3- For Logistic Regression must all comment be transformed in tensor(Array).


#### Logistic Regression model
We now define our operations in order to properly run the Logistic Regression. Logistic regression is typically thought of as a single equation:


              ŷ=sigmoid(WX+b)

              
However, for the sake of clarity, we can have it broken into its three main components: 


              a weight times features matrix multiplication operation, 
              a summation of the weighted features and a bias term, 
              and finally the application of a sigmoid function. 


#### Deep Learning Approches
In this section, I will predict the sentiment of movie reviews as either positive or negative in Python using the Keras deep learning library. 


              1-Fully connected Layers
              2-LSTM layers with Word Embeding.
### Sentiment Analysis Datasets:

<p align="center">
<img src="./img/1.JPG" alt="Sentiment Analysis Datasets " />
<p align="center">

### Sentiment Lexica:
there are a lot of sentiment lexica that can are very useful resources which can be used for problems related to the sentiment analysis:

<p align="center">
<img src="./img/2.JPG" alt="Sentiment Lexica" />
<p align="center">

