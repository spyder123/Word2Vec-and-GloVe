**Word2Vec and GloVe**



**Word2Vec**
Word2vec is an initial framework for learning word vectors.
Initially, we use a large corpus of text.
We iterate each position t in the text, which has a center word c and context (outside) words o
Then we calculate the probability of o given c (or vice versa)
We use gradient descent to maximize this probability



**GloVe**
It was found that the can ratios of co-occurrence probabilities encode meaning and understand relationships between two words, e.g., nearest words to frogs.
