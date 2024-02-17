# 🔥 NLP

1. Tokenization: "Tokenization is the process of converting the text into smaller units called tokens."
   There are different ways to do it:
     - sent_tokenize
     - word_tokenize
     - wordpunct_tokenize
     - TreebankWordTokenizer
  
2. Stemming: Stemming is used in text processing in NLP is the process of reducing a word to their root form called 'stem'. For example, the stemming process might convert words like "running," "runner," and "ran" to the common stem "run."
   There are different techniques to do it:
   - Porter Stemmer
   - Snowball Stemmer
   - Regexp Stemmer
  
3. Lemmatization: Lemmatization is also a technique used in NLP, but it goes beyond stemming by reducing words to their "lemma" or base form, which is a valid word found in the dictionary. Lemmatization involves considering the context of a word and its part of speech to produce a meaningful base form. Unlike stemming, lemmatization ensures linguistic accuracy but can be computationally more intensive.
   There is a way to do it:
   - WordNet Lemmatizer
