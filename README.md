 
# Self Learning Chatbot using Python and NLTK
A chatbot is a computer program designed to simulate conversation with human users, especially over the internet.

A self-learning chatbot, also known as an AI or intelligent chatbot, is a type that uses machine learning algorithms to enhance its performance over time continuously. This indicates that the chatbot can acquire knowledge from user interactions and modify its responses accordingly.

## Why are chatbots important?

### Cost and Time Effective - Humans cannot be active 24/7 but chatbots can and the replying power of chatbots is much fast than humans.
Cheap Development cost - with the advancement in technology many tools are developed that help easy development and integration of chatbots with little investment.
Human Resource - Today Chatbots can also talk with text o speech technology so it gives the feel as a human is talking on another side.
Business Branding - Businesses are changing with technology and chatbot is one out of them. Chatbot also helps in advertising, branding of organization product and services and give daily updates to users.

# Natural Language Tool Kit (NLTK)
NLTK (Natural Language Toolkit) is the go to API for NLP (Natural Language Processing) with Python. It is a really powerful tool to preprocess text data for further analysis like with ML models for instance. It helps convert text into numbers, which the model can then easily work with.
# Steps invovled in building model
### 1. Importing libraries
Necessary libraries are imported for model like numpy, nltk, string, random

### 2. Reading text corpus
A corpus is the most critical and basic building block of any NLP related application. It provides us with quantitative data that is used to build NLP applications.
In this model, data.txt file is read in which text is store from which Chatbot will learn and give responses to user.

### 3. Performing Tokenization, Stemming, Lemmatization

Tokenization : Raw text data is converted into numerical form with the help of tokenization.
Stemming : Stemming is the process of finding similarities between words with the same root words.
Lemmatization : Lemmatization refers to returning the base word.
All these steps are performed on data.

### 4. Preprocessing (Stopwords, Removal, Lower case conversion etc) step

Stopwords : Stop words are a set of commonly used words in any language. For example, in English, “the”, “is” and “and”, would easily qualify as stop words. In NLP and text mining applications, stop words are used to eliminate unimportant words, allowing applications to focus on the important words instead.

Removal : Stop words removal is the data pre-processing step in the natural language processing (NLP) pipeline in which we remove all the highly frequent words from the text as it does not add any valuable information to understand the text better resulting in the NLP model dealing with less number of features.

Lower case conversion : It is one of the most common text preprocessing Python steps where the text is converted into the same case preferably lower case.

### 5. Defining greeting functions

Model is trained with greeting inputs and return responses to user inside a function.

### 6. Response Generation by the Bot using TfidfVectorizer and cosine similarity

TfidfVectorizer : It counts the number of times a word appears in a document (using a bag-of-words approach), it also takes into account not only how many times a word appears in a document and also how important that word is to the whole corpus.

Bag Of Words : It turns arbitrary text into fixed-length vectors by counting how many times each word appears.

Cosine similarity : It measures the similarity between two vectors of an inner product space. It determines whether two vectors are pointing in the same direction by measuring the cosine of the angle between them. In text analysis, it is used to determine document similarity.

### 7. Defining the Chat Flow A chatbot flow is a structure that determines how a chatbot conversation will take place, taking into account the questions your chatbot would ask and the various replies that a user could provide. A chatbot flow is a series of paths that a user's responses could trigger.

A complete chat flow is functioned inside model so that Chatbot can give accurate answers to the user according to data provide to model through data.txt file.

### 8. Chatbot Conversation
!C:\Users\AYUSH NATH TIWARI\Pictures\Screenshots
