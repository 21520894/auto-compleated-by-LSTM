# auto-compleated-by-LSTM
simple autocomplete by using tokenize word and using LSTM for predicting next words

##LSTM
March 2022) Long short-term memory (LSTM) is a type of recurrent neural network (RNN) aimed at mitigating the vanishing gradient problem commonly encountered by traditional RNNs. Its relative insensitivity to gap length is its advantage over other RNNs, hidden Markov models, and other sequence learning methods.

## Trie structure

The Trie data structure is a tree-like data structure used for storing a dynamic set of strings. It is commonly used for efficient retrieval and storage of keys in a large dataset. Trie supports operations such as insertion, search, and deletion of keys, making it a valuable tool in fields like computer science and information retrieval. In this article we are going to explore insertion and search operation in Trie Data Structure

We will use trie structure for predicting whether the word being entered is correct or not and predict the word to be corrected

## Ngram

In this module we build the n-gram Language Model. In the process, we learn a lot of the basics of machine learning (training, evaluation, data splits, hyperparameters, overfitting) and the basics of autoregressive language modeling (tokenization, next token prediction, perplexity, sampling). GPT is "just" a very large n-gram model, too. The only difference is that GPT uses a neural network to calculate the probability of the next token, while n-gram uses a simple count-based approach.

Ngram will be used for calculating the probability of the number of words that should be predicted next

#data
Dataset has 5772 words, dataset is taken from twitter posts and comments (now x) expressing different shades of emotions.

Link of dataset [link](https://drive.google.com/file/d/132dnmXzKV9TaURcP0B22Q11i1pKX9L9q/view?usp=drive_link)

