Models of different architectures, based on Recurrent Neural Networks (LSTM & GRU), as well as Convolutional Neural Networks, were developed with Keras, trained and evaluated in the task of sentiment analysis with Stanford's IMDB Dataset. 
Specifically, the training and testing datasets were used, containing 50,000 reviews, of which 25,000 were positive and 25,000 were negative. 

The split for training/validation/test set was 80:10:10. Six models were developed with the Keras framework, 
and trained with both custom embeddings (embedding layer) and the pre-trained Glove embeddings. 

Another 1 model was developed with the Pytorch framework, with which experiments were performed in the same way, 
as well as with different options in data cleaning (with and without punctuation).
