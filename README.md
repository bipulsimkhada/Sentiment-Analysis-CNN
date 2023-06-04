# Sentiment-Analysis-CNN

## CNN for Natural Language Processing (NLP)
Convolutional Neural Networks (CNNs) are a class of neural networks that are widely used in image processing tasks, but they can also be used in Natural Language Processing (NLP) tasks. In NLP, CNNs can be used to process and analyze text data, especially in tasks that involve text classification, sentiment analysis, and language modeling.

CNNs can be used to classify the sentiment of text into positive, negative, or neutral. In this approach, the text is converted into a matrix of word embeddings or one-hot encoded vectors, and then processed through a series of convolutional layers, pooling layers, and fully connected layers. The output layer produces a vector of probabilities for each sentiment label. CNN-based sentiment analysis models have shown good performance in various NLP tasks such as product review analysis and social media sentiment analysis.

## Libraries 
* Keras
* numpy
* pandas
* BeautifulSoup

## Tool
* Google Colab
* Google Drive

## Dataset
Dataset Link: http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip

## CNN for Sentiment Analysis
In this project, we used the dataset containing tweets and labeled sentiment from Stanford University. We trained our model for sentiment analysis from the tweets with 0 being negative and 1 being positive. Here are the steps involved:
* Import the dataset into the google drive and mount the google drive. 
* Clean the data to remove redundant characters (numbers and symbols) that do not add any value to the sentences.
* Find the max length of the sentence. Assign token to the words and add padding for the remaining. 
* Splitting data into training and testing set. 
* Model for CNN bigram followed by trigram, fourgram, dense layer and output. 
* The model is configured, compiled, and fitted. 

## Model Evaluation
Input:  great job. keep it up<br>
Output: 0.9969422

Input:  I am not happy with your performance.<br>
Output: 0.02016165
