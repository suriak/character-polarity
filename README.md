## Drilling Beyond Word Boundaries - Polarity analysis of English alphabets.

This is a fun experiment in which the sentiment (polarity) of each of the 26 English alphabet is computed. The polarity is calculated using a sentiment lexicon.

Once the sentiment of each alphabet is found, then it can be used to measure the polarity of words/phrases. Please note that, this score is the direct reflection of the score of the individual alphabets in the words and doesn't necessarily reflect any semantics of the word/phrases.

1. [Stanford Sentiment Lexicon](https://nlp.stanford.edu/projects/socialsent/) is used for computing character polarity. This is supplied in the repository (`socialsent_hist_adj` and `socialsent_hist_freq`)
2. Implemented in Python 3.6.
3. Code and analysis is available is the notebook shared(`alphabet_polarity.ipynb`). 


## What are the most positive and negative English alphabets?!!
* `[('m', 71), ('s', 99), ('p', 116)]` are the most positive alphabets. 
* `[('i', -25), ('d', -14), ('k', -3)]` are the most negative alphabets.

## How is the sentiment of few English words?
* Polarity of word 'happy' is 56.0
* Polarity of word 'hero' is 19.25
* Polarity of word 'die' is -8.67
* Polarity of word 'idle' is -1.25

### Notes:
1. In this implementation, the lexicon is build using the frequent words from the year 2000. The lexicon can be enriched further by adding words from the rest of the years.
2. The polarity value for all 26 English alphabet is below.<br>
`{'a': 17, 'b': 28, 'c': 27, 'd': -14, 'e': 13, 'f': 11, 'g': 49, 'h': 20, 'i': -25, 'j': 18, 'k': -3, 'l': 21, 'm': 71, 'n': 14, 'o': 7, 'p': 116, 'q': 5, 'r': 37, 's': 99, 't': 46, 'u': 6, 'v': 5, 'w': 18, 'x': 1, 'y': 11, 'z': -2}`
