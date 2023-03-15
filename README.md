# DL4Depression
This code contains a classification task to distinguish “depression” and “non-depression” tweets using two different architectures: Bi LSTM with attention and BERT.
This is part of a final project that aims to show the concepts and skills learned on the “Deep Learning for NLP” course of the LCT Master program at the UPV. 

DATA SET

The full data set used was created ad hoc by combining two open datasets already available online:

- Around 2000 tweets from the Sentiment140 dataset labeled as 0 ("no-depression").
- Around 2000 tweets from a GitHub repository labeled as 1 (“depression”).

The pre-process includes lowercasing, tokenization, remove punctuation, numbers and symbols and not remove function words. 
The embeddings were created from Glove pre-trained on Twitter.

MODELS

Two different architectures were compared:

- Bi LSTM with attention (see code) 
- fine-tuned BERT (see code)

CONCLUSION

Comparing accuracy, and as it was expected, the BERT model outperformed the LSTM.
