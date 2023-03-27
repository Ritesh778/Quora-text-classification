# Quora-text-classification
This is project is based on the text classification using NLP.

# Prerequisites
    -pip install scikit-learn
    -pip install pandas
    -pip install numpy
    -pip install nltk

# Text Classification with bag of words
    Outline:
       -Download and explore the data
       -Apply text preprocessing techniques
       -Implement the bag of words model
       -Train ML models for text classification
       -Make predictions and submit to Kaggle
       
# Download and Explore the Data
     Outline:
        -Download the dataset from kaggle to jupyter notebook
        -Explore the data using Pandas
        -Create a small working sample
        
# Text Preprocessing Techniques
    Outline:
        -Understand the bag of words model
        -Tokenization
        -Stop word removal
        -Stemming
#### Bag of words Intution
       -Create a list of all the words across all the text documents
       -Convert each document inot vector counts of each word
    Limitations:
       -There may be too many words in the dataset
       -Some words may occur to frequently
       -Some words may occur very rarely or only once
       -A single word may have many forms(go,gone,going or bird vs birds)
### Tokenization 
    Splitting a document into words and seperators

### Stop Word Removal
    Removing commonly occuring words

### Stemming
     Stemming is the process of reducing a word to its base or root form, also known as a stem, by removing any prefixes or suffixes. The resulting stem may not      necessarily be a word itself, but it represents the core meaning of the word.
     Example:-"go","gone","going" ->"go
             "birds","bird" -> "bird"
             
 # Implement Bag of Words
    Outline:
        -Create a vocabulary using Count Vectorizer
        -Transform text to vectors using Count Vectorizer
        -Configure text preprocessing in Count Vectorizer
 
 # ML Models for Text Classification

    outline:
        -Create a training & validation set
        -Train a logisitic regression model
        -Make predicions on training,validation & test data


Dataset link :- https://www.kaggle.com/competitions/quora-insincere-questions-classification
