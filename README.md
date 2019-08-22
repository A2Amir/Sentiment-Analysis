# Sentiment-Analysis
Sentiment Analysis with logistic Regression and Fully Connected layer and LSTM (Tensorflow)

I am going to looking at how to apply Logistic Regression to the task of sentiment analysis. Sentiment analysis can be thought of as the exercise of taking a sentence, paragraph, document, or any piece of natural language, and determining whether that text is emotional tone is positive or negative. 


Logistic Regression model
We now define our operations in order to properly run the Logistic Regression. Logistic regression is typically thought of as a single equation:


              ŷ=sigmoid(WX+b)
              ŷ=sigmoid(WX+b)
              
However, for the sake of clarity, we can have it broken into its three main components: 


              a weight times features matrix multiplication operation, 
              a summation of the weighted features and a bias term, 
              and finally the application of a sigmoid function. 


Deep Learning Approches

In this section, I will predict the sentiment of movie reviews as either positive or negative in Python using the Keras deep learning library. 


              1-Fully connected Layers
              2-LSTM layers with Word Embeding.
