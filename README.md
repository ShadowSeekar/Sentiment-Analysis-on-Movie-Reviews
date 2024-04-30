# Sentiment-Analysis-on-Movie-Reviews
This study aims to delve into the sentiment dynamics present in movie reviews, exploring how viewers perceive and articulate their emotional responses to cinematic experiences. Leveraging state-of-the-art NLP techniques, we seek to discern patterns, trends, and nuances in sentiment expression across a diverse range of films.

Split the dataset, 20% of the data will be reserved for testing, while the remaining 80% will be used for training.
Embedding layer converts our textual data into numeric form. It is then used as the first layer for the deep learning models in Keras. 
Embedding layer expects the words to be in numeric form .

Import GloVe Word Embedding to build Embedding Dictionary and use this to build Embedding Matrix for our Corpus.
Create Embedding Matrix having 100 columns containing 100-dimensional GloVe word embeddings for all words in our corpus.
Words that do not have pretrained embeddings will have a row of zeros in the embedding matrix. This embedding matrix can then be used to initialize the embedding layer of a neural network model for natural language processing tasks, allowing the model to leverage pretrained word embeddings during training.
