# Sentiment-Analysis using Python

Sentiment Analysis using Tensorflow/Keras of Hotel_Review.csv

### Steps:

1. Imported necessary libraries: pandas, matplotlib, numpy, seaborn, and TensorFlow modules.
2. Loaded a dataset from a CSV file containing hotel reviews.
3. Preprocessed the data by combining positive and negative reviews, creating a binary sentiment classification (positive/negative).
4. Balanced the dataset by resampling positive reviews to match the number of negative reviews.
5. Tokenized the text data and converted it into sequences of integers.
6. Defined a Sequential model in Keras with an embedding layer, LSTM layer, and dense layer for sentiment analysis.
7. Compiled the model with binary cross-entropy loss and Adam optimizer.
8. Trained the model on the padded sequences of text data.
9. Defined a function to predict sentiment label (positive/negative) for new text inputs.
10. Demonstrated the sentiment prediction function on two sample sentences.
