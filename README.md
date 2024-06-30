# NLP_Challenges
This repository contains a collection of Natural Language Processing challenges and their solutions. They cover a variety of NLP tasks and models to solve them.

## Challenge 1
It uses the well-known 20 Newsgroups dataset to apply TF-IDF as a vectorization technique and then apply the cosine distance to analyze the similarity of documents. Finally, it also implements Naive Bayes to classify them.

## Challenge 2
This challenge takes Immanuel Kant's Critique of Pure Reason as a corpus and uses Word2Vec to perform a custom embedding vectorization on it. It then analyzes how well the embeddings capture similarities between terms in the context of the thought of this philosopher using the cosine distance. Lastly, it uses T-SNE as a dimentionality reduction techique in order to be able to visualize the vectors in 2 and in 3 dimensional spaces.

## Challenge 3
This one tries to implement a language model that predicts the next term, given a sequence. It's actually divided in two notebooks: One of them takes words as terms and it's applied on a restaurant reviews dataset. The other one aims at predicting the next character, instead of the full word, and it's tested on TED Talks about computers transcriptions in English. They are both implemented in Keras and use LSTM based networks to perform the task. Other than that, they also add an implementation of Beam Search, both stochastic and deterministic, to make the predictions.

## Challenge 4
This network is a Bot that attempts to be capable of answering questions. It's trained on the Conversational Intelligence Challenge 2. To do so it uses an encoder-decoder architecture based on LSTMs.

## Challenge 5
This one uses the BERT transformer architecture to perform sentiment analysis on a Google apps reviews dataset. The reviews fall under 1 out of 5 possible classes. Further development could be done on this notebook by adding fine tunning on BERT.