# Sentiment-classification

In this project I had to built a Sentiment Classification model which can tell whether a movie review is positive or negative. I used the IMDB Dataset which was already present in Keras library.

I maped each word onto a 35 length real valued vector. I also limited the total number of words that we are interested in modeling to the 6000 most frequent words, and zero out the rest. Finally, the sequence length (number of words) in each review varies, so I constrained each review to be 600 words, truncating long reviews and pad the shorter reviews with zero values.

First I built a simple LSTM Model. After that I added the Dropout layers on in. Then I added CNN layer on that model.

Final accuracy of model is 87.27% .
