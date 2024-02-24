# 🔥 NLP

1. **Tokenization**: "Tokenization is the process of converting the text into smaller units called tokens."
   There are different ways to do it:
     - sent_tokenize
     - word_tokenize
     - wordpunct_tokenize
     - TreebankWordTokenizer
  
2. **Stemming**: Stemming is used in text processing in NLP is the process of reducing a word to their root form called 'stem'. For example, the stemming process might convert words like "running," "runner," and "ran" to the common stem "run."
   There are different techniques to do it:
   - Porter Stemmer
   - Snowball Stemmer
   - Regexp Stemmer
  
3. **Lemmatization**: Lemmatization is also a technique used in NLP, but it goes beyond stemming by reducing words to their "lemma" or base form, which is a valid word found in the dictionary. Lemmatization involves considering the context of a word and its part of speech to produce a meaningful base form. Unlike stemming, lemmatization ensures linguistic accuracy but can be computationally more intensive.
   There is a way to do it:
   - WordNet Lemmatizer

4. **Parts of Speech Tagging**: Part-of-speech (POS) tagging is a crucial task in Natural Language Processing (NLP) that involves assigning a specific grammatical category (such as noun, verb, adjective, etc.) to each word in a sentence. POS tagging is essential for various NLP applications, including text analysis, information retrieval, and machine translation. Here are some common parts of speech and their abbreviations:

- Noun (NN): A word that represents a person, place, thing, or idea. Example: "dog," "city," "happiness."
- Verb (VB): A word that expresses an action or a state of being. Example: "run," "eat," "is."
- Adjective (JJ): A word that describes or modifies a noun. Example: "happy," "red," "tall."
- Adverb (RB): A word that modifies a verb, adjective, or another adverb, often providing information about time, manner, place, or degree. Example: "quickly," "very," "here."
- Pronoun (PRP): A word that takes the place of a noun. Example: "he," "she," "it."
- Preposition (IN): A word that shows the relationship between a noun (or pronoun) and other words in a sentence. Example: "in," "on," "under."
- Conjunction (CC): A word that connects words, phrases, or clauses. Example: "and," "but," "or."
- Interjection (UH): A word or phrase that expresses strong emotion. Example: "wow," "ouch," "oh."
- Determiner (DT): A word that introduces a noun and identifies it in terms of quantity, possession, or definiteness. Example: "the," "some," "my."
- Modal (MD): A verb that expresses possibility, necessity, or ability. Example: "can," "may," "must."

- 5. **Named Entity Recognition:** Named Entity Recognition (NER) is a natural language processing (NLP) task that involves identifying and classifying named entities (such as persons, organizations, locations, dates, and more) in a text. The goal of NER is to extract structured information from unstructured text, making it easier to understand and analyze.

**For Example**:

"This Metal Estate company was established in 1920 in Pakistan with budget of 1 million dollars, which takes around 5 years."

**NER will do this**:

- Organization: Metal State
- Place: Pakistan
- Century: 1920
- Money: 1 million dollars
- Time: 5 years

