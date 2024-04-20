# Sentiment-Analysis using Python

Sentiment Analysis using Tensorflow/Keras of Hotel_Review.csv

### <u>Steps:</u>
Firstly, imported necessary libraries: pandas, matplotlib, numpy, seaborn, and TensorFlow modules.

Loaded a dataset from a CSV file containing hotel reviews.

Preprocessed the data by combining positive and negative reviews, creating a binary sentiment classification (positive/negative).
Balanced the dataset by resampling positive reviews to match the number of negative reviews.
Tokenized the text data and converted it into sequences of integers.
Defined a Sequential model in Keras with an embedding layer, LSTM layer, and dense layer for sentiment analysis.
Compiled the model with binary cross-entropy loss and Adam optimizer.
Trained the model on the padded sequences of text data.
Defined a function to predict sentiment label (positive/negative) for new text inputs.
Demonstrated the sentiment prediction function on two sample sentences.
